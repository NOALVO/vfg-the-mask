# vfg-the-mask
Masked input for [Vue Form Generator](https://github.com/vue-generators) using [Vue The Mask](https://vuejs-tips.github.io/vue-the-mask/)

## How to use

> ⚠ There is no npm package to use it. Copy the `VfgTheMask.vue` file to your project and follow the steps below.

### Declare the required plugins/components at your main application file

```javascript
import VueFormGenerator from 'vue-form-generator';
import VueTheMask from 'vue-the-mask';
import VfgTheMask from './components/VfgTheMask';

Vue.use(VueFormGenerator);
Vue.use(VueTheMask);
Vue.component('field-vfg-the-mask', VfgTheMask);
```

### Use the type `"vfg-the-mask"` and declare the `mask` property at your field's schema

```
{
    model: 'mydate',
    type: 'vfg-the-mask',
    mask: '##/##/####'
}
```

## Support

❗ We will not provide support related for Vue Form Generator neither Vue The Mask. If you need support with these projects, go to their GitHub repositories: [Vue Form Generator](https://github.com/vue-generators) | [Vue The Mask](https://vuejs-tips.github.io/vue-the-mask/)
