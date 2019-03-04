# pyhelpers
(Version 0.0.1)

This package contains a few helper functions to facilitate trivial processes, such as prompting confirmation (yes/no), saving and loading pickle/json files.



#### Quick Start

```python
import pyhelpers
```



###### A confirmation of whether to continue is needed:

```python
pyhelpers.confirmed(prompt="Continue?...")
```



###### To save/load a variable as a pickle file:

```python
ex_var = 1

pyhelpers.save_pickle(ex_var, "C:/Users/user_name/ex_var.pickle")
```

To load the pickle file:

```python
pyhelpers.load_pickle("C:/Users/user_name/ex_var.pickle")
```





#### References:

[1] http://pydriosm.activestate.com/recipes/541096-prompt-the-user-for-confirmation/

[2] https://stackoverflow.com/questions/37573483/progress-bar-while-download-file-over-http-with-requests

[3] https://stackoverflow.com/questions/3232943/update-value-of-a-nested-dictionary-of-varying-depth

