# benchttp/action

This action runs Benchttp CLI from the host repository.

## Inputs

| Name                | Description                                                 | Default value |
| ------------------- | ----------------------------------------------------------- | :-----------: |
| `options`           | **Required** CLI arguments following "benchttp run" command |       -       |
| `working-directory` | _Optional_ CLI arguments following "benchttp run" command   |     `"."`     |
| `version`           | _Optional_ Version of Benchttp CLI to use                   |   `latest`    |

**Optional** Version of Benchttp CLI to use

## Example usage

```yaml
uses: benchttp/action@v1
with:
  version: v0.1.0
  options: -configFile=./my-benchttp-config.yml -silent
```
