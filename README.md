# generamba-viper-compositional-layout-view-controller-catalog

It's a shared catalog of templates for [Generamba](https://github.com/strongself/Generamba) code generator.

## Usage

1. Add templates to `Rambafile` .

```yaml:Rambafile
### Templates
catalogs:
- 'https://github.com/0x0c/generamba-compositional-layout-catalog'
templates:
- {name: 0x0c_viper_compositional_layout_view_controller}
```

2. Run `generamba template install` .

3. Run `generamba gen [Module name] [Tempalate name]` .

## Templates

- [viper-compositional-layout-view-controller](https://github.com/oneinc-jp/generamba-compositional-layout-catalog/blob/main/viper-compositional-layout-view-controller/0x0c_viper_compositional_layout_view_controller.rambaspec)

# Dependencies

- [CompositionalLayoutViewController](https://github.com/oneinc-jp/CompositionalLayoutViewController)
- [CompositionalLayoutViewControllerViperExtension](https://github.com/0x0c/CompositionalLayoutViewControllerViperExtension)
