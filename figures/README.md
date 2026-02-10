# Figures Folder

Save your plots and visualizations here for use in reports and presentations.

## Naming Convention

Use descriptive names with the notebook number prefix:

```
01_target_distribution.png
01_correlation_heatmap.png
02_cap_outlier_comparison.png
03_feature_importance.png
04_model_comparison.png
```

## Saving Figures in Python

```python
# Save current plot
plt.savefig('../figures/01_my_plot.png', dpi=150, bbox_inches='tight')

# Save with transparent background (for presentations)
plt.savefig('../figures/01_my_plot.png', dpi=150, bbox_inches='tight', transparent=True)
```
