# sun-layout
Parameterized sun layout for CraftML

### Usage
```html
<craft>
    <craft name="sun-layout" module="sun-layout"/>
</craft>
```

### Parameters
- radius: adjusts radius of item arrangement

### Example
```html
<craft>
    <craft name="sun-layout" module="sun-layout"/>
    <sun-layout>
        <repeat n="10">
            <prism transform="scale(0.5)"></cube>
        </repeat>
    </sun-layout>
</craft>
```

![example](example.png)

