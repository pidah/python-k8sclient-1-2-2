## Requirements.
Python 2.7 and later.
swagger-codegen (if you intend to generate your own client)


## v1.json

Pulled from https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/swagger-spec/v1.json for Kubernetes v1.2.2

## Setuptools
You can install the bindings via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install
```

Or you can install from Github via pip:

```sh
pip install git+https://github.com/geekerzp/swagger_client.git
```

To use the bindings, import the pacakge:

```python
import swagger_client
```

## Manual Installation
If you do not wish to use setuptools, you can download the latest release.
Then, to use the bindings, import the package:

```python
import path.to.swagger_client
```

## To Generate your own swagger_client
`swagger-codegen generate -i v1.json -l python -o swagger_client`


## Documentation

`connect_delete_namespaced_pod_proxy(self,namespace,name)`

connectDELETErequeststoproxyofPod

`connect_delete_namespaced_pod_proxy_1(self,namespace,name,path2)`

connectDELETErequeststoproxyofPod

`connect_delete_namespaced_service_proxy(self,namespace,name)`

connectDELETErequeststoproxyofService

`connect_delete_namespaced_service_proxy_2(self,namespace,name,path2)`

connectDELETErequeststoproxyofService

`connect_delete_node_proxy(self,name)`

connectDELETErequeststoproxyofNode

`connect_delete_node_proxy_3(self,name,path2)`

connectDELETErequeststoproxyofNode

`connect_get_namespaced_pod_attach(self,namespace,name)`

connectGETrequeststoattachofPod

`connect_get_namespaced_pod_exec(self,namespace,name)`

connectGETrequeststoexecofPod

`connect_get_namespaced_pod_portforward(self,namespace,name)`

connectGETrequeststoportforwardofPod

`connect_get_namespaced_pod_proxy(self,namespace,name)`

connectGETrequeststoproxyofPod

`connect_get_namespaced_pod_proxy_4(self,namespace,name,path2)`

connectGETrequeststoproxyofPod

`connect_get_namespaced_service_proxy(self,namespace,name)`

connectGETrequeststoproxyofService

`connect_get_namespaced_service_proxy_5(self,namespace,name,path2)`

connectGETrequeststoproxyofService

`connect_get_node_proxy(self,name)`

connectGETrequeststoproxyofNode

`connect_get_node_proxy_6(self,name,path2)`

connectGETrequeststoproxyofNode

`connect_head_namespaced_pod_proxy(self,namespace,name)`

connectHEADrequeststoproxyofPod

`connect_head_namespaced_pod_proxy_7(self,namespace,name,path2)`

connectHEADrequeststoproxyofPod

`connect_head_namespaced_service_proxy(self,namespace,name)`

connectHEADrequeststoproxyofService

`connect_head_namespaced_service_proxy_8(self,namespace,name,path2)`

connectHEADrequeststoproxyofService

`connect_head_node_proxy(self,name)`

connectHEADrequeststoproxyofNode

`connect_head_node_proxy_9(self,name,path2)`

connectHEADrequeststoproxyofNode

`connect_options_namespaced_pod_proxy(self,namespace,name)`

connectOPTIONSrequeststoproxyofPod

`connect_options_namespaced_pod_proxy_10(self,namespace,name,path2)`

connectOPTIONSrequeststoproxyofPod

`connect_options_namespaced_service_proxy(self,namespace,name)`

connectOPTIONSrequeststoproxyofService

`connect_options_namespaced_service_proxy_11(self,namespace,name,path2)`

connectOPTIONSrequeststoproxyofService

`connect_options_node_proxy(self,name)`

connectOPTIONSrequeststoproxyofNode

`connect_options_node_proxy_12(self,name,path2)`

connectOPTIONSrequeststoproxyofNode

`connect_post_namespaced_pod_attach(self,namespace,name)`

connectPOSTrequeststoattachofPod

`connect_post_namespaced_pod_exec(self,namespace,name)`

connectPOSTrequeststoexecofPod

`connect_post_namespaced_pod_portforward(self,namespace,name)`

connectPOSTrequeststoportforwardofPod

`connect_post_namespaced_pod_proxy(self,namespace,name)`

connectPOSTrequeststoproxyofPod

`connect_post_namespaced_pod_proxy_13(self,namespace,name,path2)`

connectPOSTrequeststoproxyofPod

`connect_post_namespaced_service_proxy(self,namespace,name)`

connectPOSTrequeststoproxyofService

`connect_post_namespaced_service_proxy_14(self,namespace,name,path2)`

connectPOSTrequeststoproxyofService

`connect_post_node_proxy(self,name)`

connectPOSTrequeststoproxyofNode

`connect_post_node_proxy_15(self,name,path2)`

connectPOSTrequeststoproxyofNode

`connect_put_namespaced_pod_proxy(self,namespace,name)`

connectPUTrequeststoproxyofPod

`connect_put_namespaced_pod_proxy_16(self,namespace,name,path2)`

connectPUTrequeststoproxyofPod

`connect_put_namespaced_service_proxy(self,namespace,name)`

connectPUTrequeststoproxyofService

`connect_put_namespaced_service_proxy_17(self,namespace,name,path2)`

connectPUTrequeststoproxyofService

`connect_put_node_proxy(self,name)`

connectPUTrequeststoproxyofNode

`connect_put_node_proxy_18(self,name,path2)`

connectPUTrequeststoproxyofNode

`create_namespace(self,body)`

createaNamespace

`create_namespaced_binding(self,body,namespace)`

createaBinding

`create_namespaced_binding_binding(self,body,namespace,name)`

createbindingofaBinding

`create_namespaced_config_map(self,body,namespace)`

createaConfigMap

`create_namespaced_endpoints(self,body,namespace)`

createaEndpoints

`create_namespaced_event(self,body,namespace)`

createaEvent

`create_namespaced_limit_range(self,body,namespace)`

createaLimitRange

`create_namespaced_persistent_volume_claim(self,body,namespace)`

createaPersistentVolumeClaim

`create_namespaced_pod(self,body,namespace)`

createaPod

`create_namespaced_pod_template(self,body,namespace)`

createaPodTemplate

`create_namespaced_replication_controller(self,body,namespace)`

createaReplicationController

`create_namespaced_resource_quota(self,body,namespace)`

createaResourceQuota

`create_namespaced_secret(self,body,namespace)`

createaSecret

`create_namespaced_service(self,body,namespace)`

createaService

`create_namespaced_service_account(self,body,namespace)`

createaServiceAccount

`create_node(self,body)`

createaNode

`create_persistent_volume(self,body)`

createaPersistentVolume

`delete_namespace(self,body,name)`

deleteaNamespace

`delete_namespaced_config_map(self,body,namespace,name)`

deleteaConfigMap

`delete_namespaced_endpoints(self,body,namespace,name)`

deleteaEndpoints

`delete_namespaced_event(self,body,namespace,name)`

deleteaEvent

`delete_namespaced_limit_range(self,body,namespace,name)`

deleteaLimitRange

`delete_namespaced_persistent_volume_claim(self,body,namespace,name)`

deleteaPersistentVolumeClaim

`delete_namespaced_pod(self,body,namespace,name)`

deleteaPod

`delete_namespaced_pod_template(self,body,namespace,name)`

deleteaPodTemplate

`delete_namespaced_replication_controller(self,body,namespace,name)`

deleteaReplicationController

`delete_namespaced_resource_quota(self,body,namespace,name)`

deleteaResourceQuota

`delete_namespaced_secret(self,body,namespace,name)`

deleteaSecret

`delete_namespaced_service(self,namespace,name)`

deleteaService

`delete_namespaced_service_account(self,body,namespace,name)`

deleteaServiceAccount

`delete_node(self,body,name)`

deleteaNode

`delete_persistent_volume(self,body,name)`

deleteaPersistentVolume

`deletecollection_namespace(self)`

deletecollectionofNamespace

`deletecollection_namespaced_config_map(self,namespace)`

deletecollectionofConfigMap

`deletecollection_namespaced_endpoints(self,namespace)`

deletecollectionofEndpoints

`deletecollection_namespaced_event(self,namespace)`

deletecollectionofEvent

`deletecollection_namespaced_limit_range(self,namespace)`

deletecollectionofLimitRange

`deletecollection_namespaced_persistent_volume_claim(self,namespace)`

deletecollectionofPersistentVolumeClaim

`deletecollection_namespaced_pod(self,namespace)`

deletecollectionofPod

`deletecollection_namespaced_pod_template(self,namespace)`

deletecollectionofPodTemplate

`deletecollection_namespaced_replication_controller(self,namespace)`

deletecollectionofReplicationController

`deletecollection_namespaced_resource_quota(self,namespace)`

deletecollectionofResourceQuota

`deletecollection_namespaced_secret(self,namespace)`

deletecollectionofSecret

`deletecollection_namespaced_service_account(self,namespace)`

deletecollectionofServiceAccount

`deletecollection_node(self)`

deletecollectionofNode

`deletecollection_persistent_volume(self)`

deletecollectionofPersistentVolume

`get_api_resources(self)`

getavailableresources

`list_component_status(self)`

listobjectsofkindComponentStatus

`list_namespace(self)`

listorwatchobjectsofkindNamespace

`list_namespaced_config_map(self)`

listorwatchobjectsofkindConfigMap

`list_namespaced_config_map_19(self,namespace)`

listorwatchobjectsofkindConfigMap

`list_namespaced_endpoints(self)`

listorwatchobjectsofkindEndpoints

`list_namespaced_endpoints_20(self,namespace)`

listorwatchobjectsofkindEndpoints

`list_namespaced_event(self)`

listorwatchobjectsofkindEvent

`list_namespaced_event_21(self,namespace)`

listorwatchobjectsofkindEvent

`list_namespaced_limit_range(self)`

listorwatchobjectsofkindLimitRange

`list_namespaced_limit_range_22(self,namespace)`

listorwatchobjectsofkindLimitRange

`list_namespaced_persistent_volume_claim(self,namespace)`

listorwatchobjectsofkindPersistentVolumeClaim

`list_namespaced_persistent_volume_claim_23(self)`

listorwatchobjectsofkindPersistentVolumeClaim

`list_namespaced_pod(self,namespace)`

listorwatchobjectsofkindPod

`list_namespaced_pod_24(self)`

listorwatchobjectsofkindPod

`list_namespaced_pod_template(self,namespace)`

listorwatchobjectsofkindPodTemplate

`list_namespaced_pod_template_25(self)`

listorwatchobjectsofkindPodTemplate

`list_namespaced_replication_controller(self,namespace)`

listorwatchobjectsofkindReplicationController

`list_namespaced_replication_controller_26(self)`

listorwatchobjectsofkindReplicationController

`list_namespaced_resource_quota(self,namespace)`

listorwatchobjectsofkindResourceQuota

`list_namespaced_resource_quota_27(self)`

listorwatchobjectsofkindResourceQuota

`list_namespaced_secret(self,namespace)`

listorwatchobjectsofkindSecret

`list_namespaced_secret_28(self)`

listorwatchobjectsofkindSecret

`list_namespaced_service(self,namespace)`

listorwatchobjectsofkindService

`list_namespaced_service_29(self)`

listorwatchobjectsofkindService

`list_namespaced_service_account(self,namespace)`

listorwatchobjectsofkindServiceAccount

`list_namespaced_service_account_30(self)`

listorwatchobjectsofkindServiceAccount

`list_node(self)`

listorwatchobjectsofkindNode

`list_persistent_volume(self)`

listorwatchobjectsofkindPersistentVolume

`patch_namespace(self,body,name)`

partiallyupdatethespecifiedNamespace

`patch_namespaced_config_map(self,body,namespace,name)`

partiallyupdatethespecifiedConfigMap

`patch_namespaced_endpoints(self,body,namespace,name)`

partiallyupdatethespecifiedEndpoints

`patch_namespaced_event(self,body,namespace,name)`

partiallyupdatethespecifiedEvent

`patch_namespaced_limit_range(self,body,namespace,name)`

partiallyupdatethespecifiedLimitRange

`patch_namespaced_persistent_volume_claim(self,body,namespace,name)`

partiallyupdatethespecifiedPersistentVolumeClaim

`patch_namespaced_pod(self,body,namespace,name)`

partiallyupdatethespecifiedPod

`patch_namespaced_pod_template(self,body,namespace,name)`

partiallyupdatethespecifiedPodTemplate

`patch_namespaced_replication_controller(self,body,namespace,name)`

partiallyupdatethespecifiedReplicationController

`patch_namespaced_resource_quota(self,body,namespace,name)`

partiallyupdatethespecifiedResourceQuota

`patch_namespaced_scale_scale(self,body,namespace,name)`

partiallyupdatescaleofthespecifiedScale

`patch_namespaced_secret(self,body,namespace,name)`

partiallyupdatethespecifiedSecret

`patch_namespaced_service(self,body,namespace,name)`

partiallyupdatethespecifiedService

`patch_namespaced_service_account(self,body,namespace,name)`

partiallyupdatethespecifiedServiceAccount

`patch_node(self,body,name)`

partiallyupdatethespecifiedNode

`patch_persistent_volume(self,body,name)`

partiallyupdatethespecifiedPersistentVolume

`proxy_delete_namespaced_pod(self,namespace,name)`

proxyDELETErequeststoPod

`proxy_delete_namespaced_pod_31(self,namespace,name,path)`

proxyDELETErequeststoPod

`proxy_delete_namespaced_service(self,namespace,name)`

proxyDELETErequeststoService

`proxy_delete_namespaced_service_32(self,namespace,name,path)`

proxyDELETErequeststoService

`proxy_delete_node(self,name)`

proxyDELETErequeststoNode

`proxy_delete_node_33(self,name,path)`

proxyDELETErequeststoNode

`proxy_get_namespaced_pod(self,namespace,name)`

proxyGETrequeststoPod

`proxy_get_namespaced_pod_34(self,namespace,name,path)`

proxyGETrequeststoPod

`proxy_get_namespaced_service(self,namespace,name)`

proxyGETrequeststoService

`proxy_get_namespaced_service_35(self,namespace,name,path)`

proxyGETrequeststoService

`proxy_get_node(self,name)`

proxyGETrequeststoNode

`proxy_get_node_36(self,name,path)`

proxyGETrequeststoNode

`proxy_head_namespaced_pod(self,namespace,name)`

proxyHEADrequeststoPod

`proxy_head_namespaced_pod_37(self,namespace,name,path)`

proxyHEADrequeststoPod

`proxy_head_namespaced_service(self,namespace,name)`

proxyHEADrequeststoService

`proxy_head_namespaced_service_38(self,namespace,name,path)`

proxyHEADrequeststoService

`proxy_head_node(self,name)`

proxyHEADrequeststoNode

`proxy_head_node_39(self,name,path)`

proxyHEADrequeststoNode

`proxy_options_namespaced_pod(self,namespace,name)`

proxyOPTIONSrequeststoPod

`proxy_options_namespaced_pod_40(self,namespace,name,path)`

proxyOPTIONSrequeststoPod

`proxy_options_namespaced_service(self,namespace,name)`

proxyOPTIONSrequeststoService

`proxy_options_namespaced_service_41(self,namespace,name,path)`

proxyOPTIONSrequeststoService

`proxy_options_node(self,name)`

proxyOPTIONSrequeststoNode

`proxy_options_node_42(self,name,path)`

proxyOPTIONSrequeststoNode

`proxy_post_namespaced_pod(self,namespace,name)`

proxyPOSTrequeststoPod

`proxy_post_namespaced_pod_43(self,namespace,name,path)`

proxyPOSTrequeststoPod

`proxy_post_namespaced_service(self,namespace,name)`

proxyPOSTrequeststoService

`proxy_post_namespaced_service_44(self,namespace,name,path)`

proxyPOSTrequeststoService

`proxy_post_node(self,name)`

proxyPOSTrequeststoNode

`proxy_post_node_45(self,name,path)`

proxyPOSTrequeststoNode

`proxy_put_namespaced_pod(self,namespace,name)`

proxyPUTrequeststoPod

`proxy_put_namespaced_pod_46(self,namespace,name,path)`

proxyPUTrequeststoPod

`proxy_put_namespaced_service(self,namespace,name)`

proxyPUTrequeststoService

`proxy_put_namespaced_service_47(self,namespace,name,path)`

proxyPUTrequeststoService

`proxy_put_node(self,name)`

proxyPUTrequeststoNode

`proxy_put_node_48(self,name,path)`

proxyPUTrequeststoNode

`read_component_status(self,name)`

readthespecifiedComponentStatus

`read_namespace(self,name)`

readthespecifiedNamespace

`read_namespaced_config_map(self,namespace,name)`

readthespecifiedConfigMap

`read_namespaced_endpoints(self,namespace,name)`

readthespecifiedEndpoints

`read_namespaced_event(self,namespace,name)`

readthespecifiedEvent

`read_namespaced_limit_range(self,namespace,name)`

readthespecifiedLimitRange

`read_namespaced_persistent_volume_claim(self,namespace,name)`

readthespecifiedPersistentVolumeClaim

`read_namespaced_pod(self,namespace,name)`

readthespecifiedPod

`read_namespaced_pod_log(self,namespace,name)`

readlogofthespecifiedPod

`read_namespaced_pod_template(self,namespace,name)`

readthespecifiedPodTemplate

`read_namespaced_replication_controller(self,namespace,name)`

readthespecifiedReplicationController

`read_namespaced_resource_quota(self,namespace,name)`

readthespecifiedResourceQuota

`read_namespaced_scale_scale(self,namespace,name)`

readscaleofthespecifiedScale

`read_namespaced_secret(self,namespace,name)`

readthespecifiedSecret

`read_namespaced_service(self,namespace,name)`

readthespecifiedService

`read_namespaced_service_account(self,namespace,name)`

readthespecifiedServiceAccount

`read_node(self,name)`

readthespecifiedNode

`read_persistent_volume(self,name)`

readthespecifiedPersistentVolume

`replace_namespace(self,body,name)`

replacethespecifiedNamespace

`replace_namespace_finalize(self,body,name)`

replacefinalizeofthespecifiedNamespace

`replace_namespace_status(self,body,name)`

replacestatusofthespecifiedNamespace

`replace_namespaced_config_map(self,body,namespace,name)`

replacethespecifiedConfigMap

`replace_namespaced_endpoints(self,body,namespace,name)`

replacethespecifiedEndpoints

`replace_namespaced_event(self,body,namespace,name)`

replacethespecifiedEvent

`replace_namespaced_limit_range(self,body,namespace,name)`

replacethespecifiedLimitRange

`replace_namespaced_persistent_volume_claim(self,body,namespace,name)`

replacethespecifiedPersistentVolumeClaim

`replace_namespaced_persistent_volume_claim_status(self,body,namespace,name)`

replacestatusofthespecifiedPersistentVolumeClaim

`replace_namespaced_pod(self,body,namespace,name)`

replacethespecifiedPod

`replace_namespaced_pod_status(self,body,namespace,name)`

replacestatusofthespecifiedPod

`replace_namespaced_pod_template(self,body,namespace,name)`

replacethespecifiedPodTemplate

`replace_namespaced_replication_controller(self,body,namespace,name)`

replacethespecifiedReplicationController

`replace_namespaced_replication_controller_status(self,body,namespace,name)`

replacestatusofthespecifiedReplicationController

`replace_namespaced_resource_quota(self,body,namespace,name)`

replacethespecifiedResourceQuota

`replace_namespaced_resource_quota_status(self,body,namespace,name)`

replacestatusofthespecifiedResourceQuota

`replace_namespaced_scale_scale(self,body,namespace,name)`

replacescaleofthespecifiedScale

`replace_namespaced_secret(self,body,namespace,name)`

replacethespecifiedSecret

`replace_namespaced_service(self,body,namespace,name)`

replacethespecifiedService

`replace_namespaced_service_account(self,body,namespace,name)`

replacethespecifiedServiceAccount

`replace_namespaced_service_status(self,body,namespace,name)`

replacestatusofthespecifiedService

`replace_node(self,body,name)`

replacethespecifiedNode

`replace_node_status(self,body,name)`

replacestatusofthespecifiedNode

`replace_persistent_volume(self,body,name)`

replacethespecifiedPersistentVolume

`replace_persistent_volume_status(self,body,name)`

replacestatusofthespecifiedPersistentVolume

`watch_namespace(self,name)`

watchchangestoanobjectofkindNamespace

`watch_namespace_list(self)`

watchindividualchangestoalistofNamespace

`watch_namespaced_config_map(self,namespace,name)`

watchchangestoanobjectofkindConfigMap

`watch_namespaced_config_map_list(self)`

watchindividualchangestoalistofConfigMap

`watch_namespaced_config_map_list_49(self,namespace)`

watchindividualchangestoalistofConfigMap

`watch_namespaced_endpoints(self,namespace,name)`

watchchangestoanobjectofkindEndpoints

`watch_namespaced_endpoints_list(self)`

watchindividualchangestoalistofEndpoints

`watch_namespaced_endpoints_list_50(self,namespace)`

watchindividualchangestoalistofEndpoints

`watch_namespaced_event(self,namespace,name)`

watchchangestoanobjectofkindEvent

`watch_namespaced_event_list(self)`

watchindividualchangestoalistofEvent

`watch_namespaced_event_list_51(self,namespace)`

watchindividualchangestoalistofEvent

`watch_namespaced_limit_range(self,namespace,name)`

watchchangestoanobjectofkindLimitRange

`watch_namespaced_limit_range_list(self)`

watchindividualchangestoalistofLimitRange

`watch_namespaced_limit_range_list_52(self,namespace)`

watchindividualchangestoalistofLimitRange

`watch_namespaced_persistent_volume_claim(self,namespace,name)`

watchchangestoanobjectofkindPersistentVolumeClaim

`watch_namespaced_persistent_volume_claim_list(self,namespace)`

watchindividualchangestoalistofPersistentVolumeClaim

`watch_namespaced_persistent_volume_claim_list_53(self)`

watchindividualchangestoalistofPersistentVolumeClaim

`watch_namespaced_pod(self,namespace,name)`

watchchangestoanobjectofkindPod

`watch_namespaced_pod_list(self,namespace)`

watchindividualchangestoalistofPod

`watch_namespaced_pod_list_54(self)`

watchindividualchangestoalistofPod

`watch_namespaced_pod_template(self,namespace,name)`

watchchangestoanobjectofkindPodTemplate

`watch_namespaced_pod_template_list(self,namespace)`

watchindividualchangestoalistofPodTemplate

`watch_namespaced_pod_template_list_55(self)`

watchindividualchangestoalistofPodTemplate

`watch_namespaced_replication_controller(self,namespace,name)`

watchchangestoanobjectofkindReplicationController

`watch_namespaced_replication_controller_list(self,namespace)`

watchindividualchangestoalistofReplicationController

`watch_namespaced_replication_controller_list_56(self)`

watchindividualchangestoalistofReplicationController

`watch_namespaced_resource_quota(self,namespace,name)`

watchchangestoanobjectofkindResourceQuota

`watch_namespaced_resource_quota_list(self,namespace)`

watchindividualchangestoalistofResourceQuota

`watch_namespaced_resource_quota_list_57(self)`

watchindividualchangestoalistofResourceQuota

`watch_namespaced_secret(self,namespace,name)`

watchchangestoanobjectofkindSecret

`watch_namespaced_secret_list(self,namespace)`

watchindividualchangestoalistofSecret

`watch_namespaced_secret_list_58(self)`

watchindividualchangestoalistofSecret

`watch_namespaced_service(self,namespace,name)`

watchchangestoanobjectofkindService

`watch_namespaced_service_account(self,namespace,name)`

watchchangestoanobjectofkindServiceAccount

`watch_namespaced_service_account_list(self,namespace)`

watchindividualchangestoalistofServiceAccount

`watch_namespaced_service_account_list_59(self)`

watchindividualchangestoalistofServiceAccount

`watch_namespaced_service_list(self,namespace)`

watchindividualchangestoalistofService

`watch_namespaced_service_list_60(self)`

watchindividualchangestoalistofService

`watch_node(self,name)`

watchchangestoanobjectofkindNode

`watch_node_list(self)`

watchindividualchangestoalistofNode

`watch_persistent_volume(self,name)`

watchchangestoanobjectofkindPersistentVolume

`watch_persistent_volume_list(self)`

watchindividualchangestoalistofPersistentVolume

## Tests

(Please make sure you have [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/) installed)

 Execute the following command to run the tests in the current Python (v2 or v3) environment:

```sh
$ make test
[... magically installs dependencies and runs tests on your virtualenv]
Ran 7 tests in 19.289s

OK
```
or

```
$ mvn integration-test -rf :PythonPetstoreClientTests
Using 2195432783 as seed
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 37.594 s
[INFO] Finished at: 2015-05-16T18:00:35+08:00
[INFO] Final Memory: 11M/156M
[INFO] ------------------------------------------------------------------------
```
If you want to run the tests in all the python platforms:

```sh
$ make test-all
[... tox creates a virtualenv for every platform and runs tests inside of each]
  py27: commands succeeded
  py34: commands succeeded
  congratulations :)
```
