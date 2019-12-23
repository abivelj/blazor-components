# blazor-components
 
### Working with blazor I ended up needing some components and decided to write my own for my projects

## 1. Radio Button
Issue is that there is not two way data binding and I've made a simple radio button that does two-way data binding.

#### Usage
```csharp 
var _isChecked = false;
```

```html
<label>
    <RadioButton Name="radioExample" TItem="bool" @bind-Value="_isChecked" CheckedValue="true" /> On
</label>

<label>
    <RadioButton Name="radioExample" TItem="bool" @bind-Value="_isChecked" CheckedValue="false" /> Off
</label>
```