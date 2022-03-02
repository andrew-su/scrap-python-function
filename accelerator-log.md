# Accelerator Log

## Options
```json
{
  "functionName" : "hello",
  "gitBranch" : "main",
  "gitUrl" : "https://github.com/sample-accelerators/python-functions-accelerator.git",
  "includeTap" : true,
  "interfaceType" : "http",
  "projectName" : "python-functions-accelerator"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[0].include (Include)
┃ ┃ ┃ ┃  Info Will include [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore]
┃ ┃ ┃ ┃ Debug CODE_OF_CONDUCT.md didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug CONTRIBUTING.md didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug DEPLOYING.md matched [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> included
┃ ┃ ┃ ┃ Debug LICENSE matched [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> included
┃ ┃ ┃ ┃ Debug NOTICE matched [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> included
┃ ┃ ┃ ┃ Debug README.md didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug cloudevents/func.py didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug func.py didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug func.yaml matched [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> included
┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> excluded
┃ ┃ ┃ ┗ Debug requirements.txt matched [func.yaml, requirements.txt, LICENSE, NOTICE, DEPLOYING.md, .gitignore] -> included
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [func.py]
┃ ┃ ┃ ┃ ┃ Debug CODE_OF_CONDUCT.md didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug CONTRIBUTING.md didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug NOTICE didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/func.py didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug func.py matched [func.py] -> included
┃ ┃ ┃ ┃ ┃ Debug func.yaml didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┗ Debug requirements.txt didn't match [func.py] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [main->hello]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃  Info Condition (#interfaceType == 'cloudevents') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ Debug CODE_OF_CONDUCT.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug CONTRIBUTING.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug NOTICE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/func.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug func.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug func.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┗ Debug requirements.txt didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [functions-python->hello]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ Debug CODE_OF_CONDUCT.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug CONTRIBUTING.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug NOTICE didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug cloudevents/func.py didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug func.py didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug func.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug requirements.txt didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [https://github.com/sample-accelerators/python-functions-accelerator.git->https://github.com/s...(truncated), main->main]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[1].transformations[1] (RewritePath)
┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'config/workload.yaml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yaml, folder=config/, filename=workload.yaml, g0=config/workload.yaml, g1=config/, g2=workload.yaml, g3=workload.yaml, g4=.yaml} and was rewritten to 'config/workload.yaml'
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[5].include (Include)
┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to true
┃ ┃ ┃ ┃  Info Will include [catalog/catalog-info.yaml]
┃ ┃ ┃ ┃ Debug CODE_OF_CONDUCT.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug CONTRIBUTING.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug LICENSE didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug NOTICE didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug SECURITY.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/catalog-info.yaml] -> included
┃ ┃ ┃ ┃ Debug cloudevents/func.py didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug func.py didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug func.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug functions-icon.png didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ Debug manifest.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┗ ┗ Debug requirements.txt didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```