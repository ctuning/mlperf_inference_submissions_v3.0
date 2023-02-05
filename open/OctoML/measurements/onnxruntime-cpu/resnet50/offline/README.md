This experiment is generated using [MLCommons CM](https://github.com/mlcommons/ck)
## CM Run Command
```
cm run script \
	--tags=run,mlperf,inference,generate-run-cmds,_submission,_short \
	--implementation=reference \
	--model=resnet50 \
	--device=cpu \
	--backend=onnxruntime \
	--power=yes \
	--adr.mlperf-power-client.power_server=192.168.0.31 \
	--clean
```