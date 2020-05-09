# Create Namespace

```
dave@ubuntu-vm02:~/Desktop$ sudo k3s kubectl create namespace automagic
namespace/automagic created
```

```
DEBU[0280] TRIGGERED /registry/namespaces/automagic, revision=872, delete=false 
DEBU[0280] WATCH READ id=13, key=/registry/namespaces/automagic, revision=872 
DEBU[0280] LIST /registry/resourcequotas/automagic/, start=/registry/resourcequotas/automagic/, limit=0, rev=872 => rev=872, kvs=0, err=<nil> 
DEBU[0280] LIST /registry/resourcequotas/automagic/, start=/registry/resourcequotas/automagic/, limit=0, rev=0 => rev=872, kvs=0, err=<nil> 
DEBU[0280] CREATE /registry/serviceaccounts/automagic/default, size=112, lease=0 => rev=873, err=<nil> 
DEBU[0280] TRIGGERED /registry/serviceaccounts/automagic/default, revision=873, delete=false 
DEBU[0280] WATCH READ id=16, key=/registry/serviceaccounts/automagic/default, revision=873 
DEBU[0280] GET /registry/serviceaccounts/automagic/default, rev=0 => rev=873, kv=true, err=<nil> 
DEBU[0280] CREATE /registry/secrets/automagic/default-token-5nd9w, size=1759, lease=0 => rev=874, err=<nil> 
DEBU[0280] TRIGGERED /registry/secrets/automagic/default-token-5nd9w, revision=874, delete=false 
DEBU[0280] WATCH READ id=5, key=/registry/secrets/automagic/default-token-5nd9w, revision=874 
DEBU[0280] UPDATE /registry/serviceaccounts/automagic/default, value=147, rev=873, lease=0 => rev=875, kvrev=875, updated=true, err=<nil> 
DEBU[0280] TRIGGERED /registry/serviceaccounts/automagic/default, revision=875, delete=false 
DEBU[0280] WATCH READ id=16, key=/registry/serviceaccounts/automagic/default, revision=875 
```