# HHDO-Product-Card

Este es un paquete de pruebas de despliegue en NPM 

### Hernan

## Ejemplo


```
import {ProductCard,ProductImage,ProductTitle,ProductButtons,} from 'hhdo-product-card';

```


```
<ProductCard
    product={product}
    initialValues={{
        count: 4,
        // maxCount: 10,
    }}
>
    {
        ({ reset, isMaxCountReached, maxCount, increaseBy, count }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
                
            </>
        )
    }

</ProductCard>
```