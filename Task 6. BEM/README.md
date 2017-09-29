# Task 6. BEM

## Separators:

**Word** separator — hyphen (-). 

*Example:*

```
<div class="date-input">...</div>

.date-input{...}
```

**Block-Element** separator — double hyphen (--).

*Example:*

```
<div class="header">
 <img class="header--logo" alt="">
</div>

.header--logo{...}
```

**Element-Modifier** (Block-Modifier) separator — space ( ). 

*Example:*

```
<div class="header">
 <img class="header--logo middle" alt="">
 <button class="header--logon-button green">SIGN IN</button>
</div>

.header--logo.middle {...}
.header--logon-button.green {...}
```




