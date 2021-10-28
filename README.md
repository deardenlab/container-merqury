
Containers for [Merqury](https://github.com/marbl/merqury) with [meryl](https://github.com/marbl/meryl)

## 

**You have to use `bash -c` because of the way `merqury` uses environment variables**!

```{bash}
singularity exec container-merqury.v1.3.sif bash -c 'echo $MERQURY'
```

