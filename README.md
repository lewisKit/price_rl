# price_rl

### Installation

```shell
cd baselines
pip install -e .
cd ../gym-simple-pricing
pip install -e .
```


### Running
```Sh
cd baselines/baselines/ppo1/

# Running example
python run_price.py -env pricing-simple-v1 --num-timesteps 250000
```

### Play with learned model
```
python play.py
```
