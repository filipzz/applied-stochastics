# Exercise


Play with the Jupyter notebook: [randomWalk1.ipynb](randomWalk1.ipynb) (you may use https://colab.research.google.com/).

1. Run the code, what can you tell about the limiting distribution? Is the chain ergodic?
2. Find minimal number of changes in  **P** that would turn the chain into aperiodic.
3. Modify transition martrix to:
```python
P = np.array([[.1, .2, .3, .4],
              [.4, .1, .2, .3],
              [.4, .2, .1, .3],
              [.3, .4, .2, .1]])
```

