# full cmd

`lightweight_gan/cli.py -> train_from_folder parameters`

# train

```sh
# trin
lightweight_gan --results_dir './results' --models_dir './models' --name flowers --data ../datasets/flowers --batch-size 16 --image_size 128 --gradient-accumulate-every 1 --num-train-steps 150000

# generate
lightweight_gan --results_dir './results' --models_dir './models' --name flowers --load_from -1 --image_size 128 --generate True --generate_types ema
```
