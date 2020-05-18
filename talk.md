# Create Namespace

```
$ sudo k3s kubectl create namespace automagic
namespace/automagic created
```

## SQLite
```
$ kine --debug
DEBU[0042] CREATE /registry/namespaces/automagic, size=124, lease=0 => rev=623, err=<nil> 
DEBU[0042] TRIGGERED /registry/namespaces/automagic, revision=623, delete=false 
DEBU[0042] WATCH READ id=13, key=/registry/namespaces/automagic, revision=623 
DEBU[0042] LIST /registry/resourcequotas/automagic/, start=/registry/resourcequotas/automagic/, limit=0, rev=623 => rev=623, kvs=0, err=<nil> 
DEBU[0042] LIST /registry/resourcequotas/automagic/, start=/registry/resourcequotas/automagic/, limit=0, rev=0 => rev=623, kvs=0, err=<nil> 
DEBU[0042] CREATE /registry/serviceaccounts/automagic/default, size=112, lease=0 => rev=624, err=<nil> 
DEBU[0042] TRIGGERED /registry/serviceaccounts/automagic/default, revision=624, delete=false 
DEBU[0042] WATCH READ id=11, key=/registry/serviceaccounts/automagic/default, revision=624 
DEBU[0042] GET /registry/serviceaccounts/automagic/default, rev=0 => rev=624, kv=true, err=<nil> 
DEBU[0042] CREATE /registry/secrets/automagic/default-token-2r5lh, size=1759, lease=0 => rev=625, err=<nil> 
DEBU[0042] TRIGGERED /registry/secrets/automagic/default-token-2r5lh, revision=625, delete=false 
DEBU[0042] WATCH READ id=5, key=/registry/secrets/automagic/default-token-2r5lh, revision=625 
DEBU[0042] UPDATE /registry/serviceaccounts/automagic/default, value=147, rev=624, lease=0 => rev=626, kvrev=626, updated=true, err=<nil> 
DEBU[0042] TRIGGERED /registry/serviceaccounts/automagic/default, revision=626, delete=false 
DEBU[0042] WATCH READ id=11, key=/registry/serviceaccounts/automagic/default, revision=626 
```

## MySQL
```
$ kine --endpoint "mysql://root:password@tcp(localhost:3306)/kine" --debug
DEBU[0086] CREATE /registry/namespaces/automagic, size=124, lease=0 => rev=802, err=<nil> 
DEBU[0086] TRIGGERED /registry/namespaces/automagic, revision=802, delete=false 
DEBU[0086] WATCH READ id=8, key=/registry/namespaces/automagic, revision=802 
DEBU[0086] LIST /registry/resourcequotas/automagic/, start=/registry/resourcequotas/automagic/, limit=0, rev=802 => rev=802, kvs=0, err=<nil> 
DEBU[0086] LIST /registry/resourcequotas/automagic/, start=/registry/resourcequotas/automagic/, limit=0, rev=0 => rev=802, kvs=0, err=<nil> 
DEBU[0086] CREATE /registry/serviceaccounts/automagic/default, size=112, lease=0 => rev=803, err=<nil> 
DEBU[0086] TRIGGERED /registry/serviceaccounts/automagic/default, revision=803, delete=false 
DEBU[0086] WATCH READ id=15, key=/registry/serviceaccounts/automagic/default, revision=803 
DEBU[0086] GET /registry/serviceaccounts/automagic/default, rev=0 => rev=803, kv=true, err=<nil> 
DEBU[0086] CREATE /registry/secrets/automagic/default-token-g2h7j, size=1759, lease=0 => rev=804, err=<nil> 
DEBU[0086] TRIGGERED /registry/secrets/automagic/default-token-g2h7j, revision=804, delete=false 
DEBU[0086] WATCH READ id=11, key=/registry/secrets/automagic/default-token-g2h7j, revision=804 
DEBU[0086] UPDATE /registry/serviceaccounts/automagic/default, value=147, rev=803, lease=0 => rev=805, kvrev=805, updated=true, err=<nil> 
DEBU[0086] TRIGGERED /registry/serviceaccounts/automagic/default, revision=805, delete=false 
DEBU[0086] WATCH READ id=15, key=/registry/serviceaccounts/automagic/default, revision=805 
```

# Credit
https://github.com/rancher/kine/blob/master/examples/minimal.md