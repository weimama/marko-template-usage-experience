# marko-template-usage-experience
marko-tempalate-usage-experience

## If else condition

```javascript
<if test="data.colors.length > 0">
  IF
</if>
<else-if test="data.colors.length == 0">
</else-if>
<else>
  ELSE
</else>
```

## For loop
```javascript
<for each="i from 0 to 5">
${data.colors[i]}
</for>

    <for each="color in data.colors">
            ${color}
    </for>
```
