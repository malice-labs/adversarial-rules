# Adversarial Semgrep Rules

This is a set of Semgrep rules used against malicious source code to detect adversarial behaviors

## Malicious Rules

```bash
$ semgrep --config adversarial-rules/malicious SOURCE
```

These are more specific and targeted rules that detect behaviors in source that are most likely malicious, with a
high degree of confidence. The presence of a detection from t

## Capabilities

```bash
$ semgrep --config adversarial-rules/capabilities SOURCE
```

These are rules that can be used to recognize capabilities in source. These alone do not denote maliciousness in
the source, but can be used in tandem with the `malicious` set to highlight what behaviors is to be exhibited during execution.
