```cpp
    $command.Add((Get-PackageNameWithVersion @PSBoundParameters))
    $command.Add($Arguments)

    # '--yes' is needed to ignore confirmation required for uninstalls
```
