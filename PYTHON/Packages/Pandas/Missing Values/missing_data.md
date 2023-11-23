# Missing data

## Crux

* ```NaN```, ```NaT```, ```None``` and ```pd.NA``` are used to mark missing values in pandas
* To detect missing values - ```df.isna()``` and ```df.notna()```
* None corresponds to
    * ```NaN``` for numeric containers 
    * ```NaT``` for datetime containers 
    * ```None``` for object containers
* Missing values in calculations are considered as zero for statistical and computational methods like ```sum()```, ```mean()```
* Missing values in arithmetic calculations between pandas object propagate naturally
* Sum of empty or all-NA Series or column of DataFrame is ```0```
* Product of empty or all-NA Series or column of DataFrame is ```1```
* Missing values in GroupBy functions are ignored
* To fill missing values - ```fillna()```
* To drop the label axis with missing values - ```dropna()```
* To replace values - ```replace()```

For more detailed information along with examples - [https://pandas.pydata.org/docs/user_guide/missing_data.html](https://pandas.pydata.org/docs/user_guide/missing_data.html)
