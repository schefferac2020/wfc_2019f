# wfc_2019f

Original Python implementation [here](https://github.com/ikarth/wfc_2019f?tab=readme-ov-file).

For more general-purpose WFC information, see: https://github.com/mxgmn/WaveFunctionCollapse

## Installing

```
git clone https://github.com/ikarth/wfc_2019f.git
cd wfc_2019f
conda create -n wfc2019 python=3.10
conda activate wfc2019
pip install -r requirements.txt
python wfc_run.py -s samples_reference.xml
```

## Running a custom pattern
1. Put your pattern in ./images/samples
2. Update `samples_action_perception.xml` with your new pattern
3. Run `python wfc_run.py -s samples_reference.xml`