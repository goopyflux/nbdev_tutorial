# Tutorial on using nbdev library
> nbdev tutorial.


```python
%load_ext autoreload
%autoreload 2
```

    The autoreload extension is already loaded. To reload it, use:
      %reload_ext autoreload


## Install

`pip install nbdev_tutorial`

## How to use

```python
say_hello("GitHub")
```




    'Hello GitHub!'



```python
y = HelloSayer("Yellow")
y.say()
```




    'Hello Yellow!'


