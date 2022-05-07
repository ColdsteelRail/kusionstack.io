# object_reference

Source: [base/pkg/kusion_kubernetes/api/core/v1/object_reference.k](https://github.com/KusionStack/konfig/blob/main/base/pkg/kusion_kubernetes/api/core/v1/object_reference.k)

This is the object\_reference module in kusion\_kubernetes.api.core.v1 package.<br />This file was generated by the KCL auto-gen tool. DO NOT EDIT.<br />Editing this file might prove futile when you re-run the KCL auto-gen generate command.

## Schema ObjectReference

ObjectReference contains enough information to let you inspect or modify the referred object.

### Attributes

|Name and Description|Type|Default Value|Required|
|--------------------|----|-------------|--------|
|**apiVersion**<br />API version of the referent.|str|Undefined|optional|
|**fieldPath**<br />If referring to a piece of an object instead of an entire object, this string should contain a valid JSON/Go field access statement, such as desiredState.manifest.containers[2]. For example, if the object reference is to a container within a pod, this would take on a value like: "spec.containers{name}" (where "name" refers to the name of the container that triggered the event) or if no container name is specified "spec.containers[2]" (container with index 2 in this pod). This syntax is chosen only to have some well-defined way of referencing a part of an object.|str|Undefined|optional|
|**kind**<br />Kind of the referent. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md\#types-kinds|str|Undefined|optional|
|**name**<br />Name of the referent. More info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/\#names|str|Undefined|optional|
|**namespace**<br />Namespace of the referent. More info: https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/|str|Undefined|optional|
|**resourceVersion**<br />Specific resourceVersion to which this reference is made, if any. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md\#concurrency-control-and-consistency|str|Undefined|optional|
|**uid**<br />UID of the referent. More info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/\#uids|str|Undefined|optional|
<!-- Auto generated by kcl-doc tool, please do not edit. -->