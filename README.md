```bash
pip install hydra-submitit-launcher
python my_app.py --multirun hydra/launcher=submitit_slurm db=mysql,postgresql
```
