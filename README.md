# ISR
> ISR functions and classes for db110 and ms110 systems


This structure is an investigation of using nbdev tools to create, test and document tools for lab use.

## Install

`pip install isr`

## How to use
These are all helper analysis functions.

## db110 functions

Test the readDB110() function call from db110.py

getFieldNames(log) will read the field names from a datalog collected from GTS

```python
fn = getFieldNames('test.log')
```

```python
print(fn)
```

    ['row_number', 'Absolute_sample_number', 'pitchGimbal_run_curMode', 'pitchGimbal_run_curPosition', 'pitchGimbal_run_setPosition', 'pitchGimbal_run_errPosition', 'pitchGimbal_run_curVelocity', 'pitchGimbal_run_velError', 'pitchGimbal_run_setVelocity', 'pitchGimbal_run_errVelocity', 'pitchGimbal_run_curCommand']
    

## ms110 function

```python
readMS110()
```




    'MS110 Test0'


