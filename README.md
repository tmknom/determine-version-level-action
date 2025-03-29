# determine-version-level-action

Auto-determine version bump level from merged PR labels.

<!-- actdocs start -->

## Description

Automatically determines the version bump level (`minor`, `patch`, or `none`)
from labels on merged pull requests since the last Git tag.

## Usage

```yaml
  steps:
    - name: Determine Version Level
      uses: tmknom/determine-version-level-action@v0
```

## Inputs

N/A

## Outputs

| Name | Description |
| :--- | :---------- |
| bump-level | The determined version bump level (`minor`, `patch`, or `none`). |

<!-- actdocs end -->

## Permissions

| Scope         | Access |
| :------------ | :----- |
| contents      | read   |
| pull-requests | read   |

## FAQ

N/A

## Related projects

N/A

## Release notes

See [GitHub Releases][releases].

[releases]: https://github.com/tmknom/determine-version-level-action/releases
