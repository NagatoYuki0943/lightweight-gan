# full cmd

`lightweight_gan/cli.py -> train_from_folder parameters`

# train

```sh
# train
lightweight_gan --results-dir './results' --models-dir './models' --name flowers --data ../datasets/flowers --batch-size 12 --image-size 128 --gradient-accumulate-every 1 --save-every 2000 --evaluate_every 2000 --num-train-steps 200000

# generate
lightweight_gan --results-dir './results' --models-dir './models' --name flowers --load_from -1 --image-size 128 --generate True
```
