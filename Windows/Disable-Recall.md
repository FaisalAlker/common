## Disabling Windows Recall Feature
- Open CMD/Power Shell (Run as Administrator)
- Type > dism /online /Disable-Feature /FeatureName:Recall
- Check Recall Status > dism /online /Get-Featureinfo /FeatureName:Recall