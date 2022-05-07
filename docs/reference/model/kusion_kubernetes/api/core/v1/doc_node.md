# node

Source: [base/pkg/kusion_kubernetes/api/core/v1/node.k](https://github.com/KusionStack/konfig/blob/main/base/pkg/kusion_kubernetes/api/core/v1/node.k)

This is the node module in kusion\_kubernetes.api.core.v1 package.<br />This file was generated by the KCL auto-gen tool. DO NOT EDIT.<br />Editing this file might prove futile when you re-run the KCL auto-gen generate command.

## Schema Node

Node is a worker node in Kubernetes. Each node will have a unique identifier in the cache (i.e. in etcd).

### Attributes

|Name and Description|Type|Default Value|Required|
|--------------------|----|-------------|--------|
|**apiVersion**<br />APIVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md\#resources|"v1"|"v1"|**required**|
|**kind**<br />Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md\#types-kinds|"Node"|"Node"|**required**|
|**metadata**<br />Standard object's metadata. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md\#metadata|[apis.ObjectMeta](../../../apimachinery/apis/doc_object_meta#schema-objectmeta)|Undefined|optional|
|**spec**<br />Spec defines the behavior of a node. https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md\#spec-and-status|[NodeSpec](doc_node_spec#schema-nodespec)|Undefined|optional|
<!-- Auto generated by kcl-doc tool, please do not edit. -->