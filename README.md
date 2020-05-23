# Creating-Bacground-Image-as-ClassName

```
.icon-CRM {
    background-image: url('../icons/userSystem_ListIcons/CRM.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    width: 2rem;
    height: 2rem;
}
```

**Just like this, remember you have to put all these properties inside classname**

Then import css file to the component which you want to use this className and then:

```
<div className='icon-CRM'></div>
```
