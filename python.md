# Dataframe

Concatenate multiple dataframes

```python
        dfs = map(lambda s: self.read_history_close(s), symbols)
        res = functools.reduce(lambda a,b: a.join(b), dfs)
```

