# SLNER

## How to Run Pretraining

```bash
# Base model
$ python3 run_pretraining.py --data-dir {$BUCKET_NAME} --model-name {$BASE_OUTPUT_DIR} --hparams config/base_config.json

# Small model
$ python3 run_pretraining.py --data-dir {$BUCKET_NAME} --model-name {$SMALL_OUTPUT_DIR} --hparams config/small_config.json
```
