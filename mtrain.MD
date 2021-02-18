'''
python train.py \
   --dataset_name llff \
   --root_dir "/home/kurt/datasets/nerf/achen_000000_working" \
   --N_importance 64 --img_wh 2048 1024 \
   --num_epochs 30 --batch_size 4092 \
   --optimizer adam --lr 5e-4 \
   --lr_scheduler steplr --decay_step 10 20 --decay_gamma 0.5 \
   --exp_name exp --num_gpus 2
```