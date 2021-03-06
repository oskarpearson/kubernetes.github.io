## ComponentStatus v1

Group        | Version     | Kind
------------ | ---------- | -----------
Core | v1 | ComponentStatus



ComponentStatus (and ComponentStatusList) holds the cluster validation info.

<aside class="notice">
Appears In  <a href="#componentstatuslist-v1">ComponentStatusList</a> </aside>

Field        | Description
------------ | -----------
apiVersion <br /> *string*  | APIVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values. More info: http://releases.k8s.io/HEAD/docs/devel/api-conventions.md#resources
conditions <br /> *[ComponentCondition](#componentcondition-v1) array*  | List of component conditions observed
kind <br /> *string*  | Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase. More info: http://releases.k8s.io/HEAD/docs/devel/api-conventions.md#types-kinds
metadata <br /> *[ObjectMeta](#objectmeta-v1)*  | Standard object's metadata. More info: http://releases.k8s.io/HEAD/docs/devel/api-conventions.md#metadata

