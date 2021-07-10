# generamba-compositional-layout-catalog

It's a shared catalog of templates for [Generamba](https://github.com/strongself/Generamba) code generator.

## Usage

1. Add templates to `Rambafile` .

```yaml:Rambafile
### Templates
catalogs:
- 'https://github.com/0x0c/generamba-compositional-layout-catalog'
templates:
- {name: 0x0c_viper_compositional_layout}
```

2. Run `generamba template install` .

3. Run `generamba gen [Module name] [Tempalate name]` .

## Templates

- [compositional-layout](https://github.com/oneinc-jp/generamba-compositional-layout-catalog/blob/main/viper-compositional-layout-view-controller/0x0c_viper_compositional_layout.rambaspec)

# Dependencies

- [CompositionalLayoutViewController](https://github.com/oneinc-jp/CompositionalLayoutViewController)
- [CompositionalLayoutViewControllerViperExtension](https://github.com/0x0c/CompositionalLayoutViewControllerViperExtension)