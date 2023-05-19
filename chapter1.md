# chapter 1
``` 
static void SetAttr(void* data, int value, bool send) {
    s_dev_attr* attr = (s_dev_attr*)data;
    s_dev* dev = (s_dev*)attr->dev;
    s_gpio_sos* sos = (s_gpio_sos*)dev->pdata;
    s_node* node = attr->node;
    sos->value = val 
}
```