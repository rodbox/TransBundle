# RBTransBundle :

Trans pour RB en version Alpha

## routing :
```
rb_trans:
    resource: "@RBTransBundle/Controller/"
    type:     annotation
    prefix:   /trans
```

## config :
```
    - { resource: "@RBTransBundle/Resources/config/services.yml" }
```

## AppKernel.php :
```
 public function registerBundles()
    {
        $bundles = [
           ...
            new RB\TransBundle\RBTransBundle(),
```