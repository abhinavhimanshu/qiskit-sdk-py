# Tools to generate qasm circuits

## Bernstein-Vazirani algorithm

To generate a Bernstein-Vazirani algorithm using n qubits, type the following.

```
python bernstein_vazirani_gen.py -q 5 -o bv5
```

The resulting circuit is stored at `bv5.qasm` and its drawing at `bv5.tex`.

For more details, run the above command with `-h` or `--help` argument.
