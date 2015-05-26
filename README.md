# sun-layout
Parameterized sun layout for CraftML

### Install
	$ npm install sun-layout

### Parameters
- radius: adjusts radius of item arrangement

### Example
```html
<craft name="flower">
    <craft name="petal" module="@gist/calebhsu/bc1d9b13b2d4fb8f27cd"/>
    <craft name="sun-layout" module="sun-layout"/>
    
    <group color="crimson">
        <sun-layout radius="7">
            <repeat n="5">
                <petal transform="scale(0.5,0.5,1)"></petal>
            </repeat>
        </sun-layout>
    </group>
    
</craft>
```

![example](example.png)

