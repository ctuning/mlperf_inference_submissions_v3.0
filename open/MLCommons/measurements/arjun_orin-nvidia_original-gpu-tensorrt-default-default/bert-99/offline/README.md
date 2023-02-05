This experiment is generated using [MLCommons CM](https://github.com/mlcommons/ck)
## CM Run Command
```
cm run script \
	--tags=run,mlperf,inference,generate-run-cmds,_submission,_full \
	--implementation=nvidia-original \
	--model=bert-99 \
	--backend=tensorrt \
	--device=cuda \
	--execution_mode=valid \
	--push-to-github=on \
	--results_dir=/home/arjun/inference_3.0_results \
	--results_git_url=https://github.com/arjunsuresh/mlperf_inference_submissions_v3.0 \
	--adr.nvidia-harness.skip_preprocess=yes \
	--adr.nvidia-harness.input_format=linear \
	--adr.nvidia-harness.make_cmd=run \
	--env.LD_PRELOAD=/home/arjun/.local/lib/python3.8/site-packages/torch/lib/libgomp-d22c30c5.so.1 \
	--readme=yes \
	--regenerate_files=yes
```
## Dependent CM scripts 


1.  `cm run script --tags=detect,os`


2.  `cm run script --tags=detect,cpu`


3.  `cm run script --tags=get,sys-utils-cm`


4.  `cm run script --tags=get,python`


5.  `cm run script --tags=get,cuda`


6.  `cm run script --tags=get,cuda-devices`


7.  `cm run script --tags=get,mlcommons,inference,src,_deeplearningexamples`

## Dependent CM scripts for the MLPerf Inference Implementation


1. `cm run script --tags=detect,os`


2. `cm run script --tags=detect,cpu`


3. `cm run script --tags=get,sys-utils-cm`


4. `cm run script --tags=get,cuda,_cudnn`


5. `cm run script --tags=get,tensorrt`


6. `cm run script --tags=build,nvidia,inference,server`


7. `cm run script --tags=get,mlcommons,inference,src,_deeplearningexamples`


8. `cm run script --tags=get,nvidia,mlperf,inference,common-code,_custom`


9. `cm run script --tags=generate,user-conf,mlperf,inference`
