This experiment is generated using [MLCommons CM](https://github.com/mlcommons/ck)
## CM Run Command
```
cm run script \
	--tags=run,mlperf,inference,generate-run-cmds,_full,_submission \
	--implementation=reference \
	--model=bert-99 \
	--backend=deepsparse \
	--device=cpu \
	--execution_mode=valid \
	--results_dir=/home/arjun/inference_3.0_results \
	--results_git_url=https://github.com/ctuning/mlperf_inference_submissions_v3.0 \
	--quiet \
	--test_query_count=10 \
	--scenario=SingleStream
```
## Dependent CM scripts 


1.  `cm run script --tags=detect,os`


2.  `cm run script --tags=get,sys-utils-cm`


3.  `cm run script --tags=get,python`


4.  `cm run script --tags=get,mlcommons,inference,src,_deeplearningexamples`
