# `code-link` Limitations

## [`link--line-numbers.qmd`](./link--line-numbers.qmd)

```yaml
# implicit/default 
```

- All good.

## [`link-true--line-numbers.qmd`](./link-true--line-numbers.qmd)

```yaml
code-link: true
```

- All good.

## [`link-true--line-numbers-true.qmd`](./link-true--line-numbers-true.qmd)

```yaml
code-link: true
code-line-numbers: true
```

- No code linking (_known limitation_).

## [`link-true--line-numbers-false.qmd`](./link-true--line-numbers-false.qmd)

```yaml
code-link: true
code-line-numbers: false
```

- All good.
