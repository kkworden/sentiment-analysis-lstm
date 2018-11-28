Forked in order to get working on macOS Mojave.

To get working:

```
conda create -n <some_name>
conda activate <some_name>
conda install sklearn tensorflow keras
python lstm.py
```

You will need to download the (Yelp dataset)[https://www.yelp.com/dataset]. You should be able to tweak the script to read from the file you want.
