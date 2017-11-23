# Break Spacing

### Run
``` 
 npm install XXX
```

### Code

```sass
    header, section {
        @include break-spacing(1, 'margin-bottom');
    }

    /*
    return CSS
    
    @media (max-width: 575px) {
        header, section {
            margin-bottom: 30px; 
        } 
    }
    
    @media (min-width: 576px) and (max-width: 767px) {
        header, section {
            margin-bottom: 37.5px; 
        } 
    }
    
    @media (min-width: 768px) and (max-width: 991px) {
        header, section {
            margin-bottom: 45px; 
        } 
    }
    @media (min-width: 992px) and (max-width: 1199px) {
        header, section {
            margin-bottom: 52.5px; 
        } 
    }

    @media (min-width: 1200px) {
        header, section {
            margin-bottom: 60px; 
        }
     }
    */

```

```sass
    header, section {
        @include break-spacing(1, 'margin-bottom' 'padding-bottom');
    }

    /*
    return CSS
    
    @media (max-width: 575px) {
        header, section {
            margin-bottom: 30px; 
            padding-bottom: 30px; 
        } 
    }
    
    @media (min-width: 576px) and (max-width: 767px) {
        header, section {
            margin-bottom: 37.5px; 
            padding-bottom: 37.5px; 
        } 
    }
    
    @media (min-width: 768px) and (max-width: 991px) {
        header, section {
            margin-bottom: 45px; 
            padding-bottom: 45px; 
        } 
    }
    @media (min-width: 992px) and (max-width: 1199px) {
        header, section {
            margin-bottom: 52.5px; 
            padding-bottom: 52.5px; 
        } 
    }

    @media (min-width: 1200px) {
        header, section {
            margin-bottom: 60px; 
            padding-bottom: 60px; 
        }
     }

    */

```
