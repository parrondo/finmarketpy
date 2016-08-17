# finmarketpy

finmarketpy is a Python based library that enables you to analyze market data and also to backtest trading strategies using
a simple to use API.

I had previously written the open source PyThalesians financial library. This new finmarketpy library has similar functionality to the 
trading part of that library. However, I've totally rewritten the API to make it much cleaner and easier to use, as well as having many 
new features. It requires the libraries chartpy (for charts) and findatapy (for loading market data) to function.

* Please bear in mind at present finmarketpy is currently a highly experimental alpha project and isn't yet fully 
documented
* Uses Apache 2.0 licence

# Gallery

To appear

# Requirements

Major requirements
* Required: Python 3.4, 3.5
* Required: pandas 0.18, numpy etc.
* Required: findatapy for downloading market data (https://github.com/cuemacro/findatapy)
* Required: chartpy for funky interactive plots (https://github.com/cuemacro/chartpy)
* Recommended: multiprocessor_on_dill because standard multiprocessing library pickle causes issues 
(from https://github.com/sixty-north/multiprocessing_on_dill)

# Installation

You can install the library using the below. After installation:
* Make sure you edit the MarketConstants file

```
pip install git+https://github.com/cuemacro/finmarketpy.git
```

But beforehand please make sure you have already installed both chartpy, findatapy and any other dependencies

```
pip install git+https://github.com/cuemacro/chartpy.git
pip install git+https://github.com/cuemacro/findatapy.git
```

# findatapy examples

In findatapy/examples you will find several demos

# Release Notes

* No formal releases yet

# Coding log

* 17 Aug 2016 - Uploaded first code

End of note
