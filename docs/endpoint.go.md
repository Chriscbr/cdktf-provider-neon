# `neon_endpoint`

Refer to the Terraform Registory for docs: [`neon_endpoint`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint).

# `endpoint` Submodule <a name="`endpoint` Submodule" id="@cdktf/provider-neon.endpoint"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Endpoint <a name="Endpoint" id="@cdktf/provider-neon.endpoint.Endpoint"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint neon_endpoint}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/endpoint"

endpoint.NewEndpoint(scope Construct, id *string, config EndpointConfig) Endpoint
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig">EndpointConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-neon.endpoint.EndpointConfig">EndpointConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMaxCu">ResetAutoscalingLimitMaxCu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMinCu">ResetAutoscalingLimitMinCu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetComputeProvisioner">ResetComputeProvisioner</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetDisabled">ResetDisabled</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetPgSettings">ResetPgSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetPoolerEnabled">ResetPoolerEnabled</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetPoolerMode">ResetPoolerMode</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetRegionId">ResetRegionId</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetSuspendTimeoutSeconds">ResetSuspendTimeoutSeconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetType">ResetType</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktf/provider-neon.endpoint.Endpoint.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-neon.endpoint.Endpoint.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-neon.endpoint.Endpoint.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget"></a>

```go
func AddMoveTarget(moveTarget *string)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget.parameter.moveTarget"></a>

- *Type:* *string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `ImportFrom` <a name="ImportFrom" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom"></a>

```go
func ImportFrom(id *string, provider TerraformProvider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.id"></a>

- *Type:* *string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.provider"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `MoveTo` <a name="MoveTo" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo"></a>

```go
func MoveTo(moveTarget *string, index interface{})
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.moveTarget"></a>

- *Type:* *string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.index"></a>

- *Type:* interface{}

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `ResetAutoscalingLimitMaxCu` <a name="ResetAutoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMaxCu"></a>

```go
func ResetAutoscalingLimitMaxCu()
```

##### `ResetAutoscalingLimitMinCu` <a name="ResetAutoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMinCu"></a>

```go
func ResetAutoscalingLimitMinCu()
```

##### `ResetComputeProvisioner` <a name="ResetComputeProvisioner" id="@cdktf/provider-neon.endpoint.Endpoint.resetComputeProvisioner"></a>

```go
func ResetComputeProvisioner()
```

##### `ResetDisabled` <a name="ResetDisabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetDisabled"></a>

```go
func ResetDisabled()
```

##### `ResetPgSettings` <a name="ResetPgSettings" id="@cdktf/provider-neon.endpoint.Endpoint.resetPgSettings"></a>

```go
func ResetPgSettings()
```

##### `ResetPoolerEnabled` <a name="ResetPoolerEnabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerEnabled"></a>

```go
func ResetPoolerEnabled()
```

##### `ResetPoolerMode` <a name="ResetPoolerMode" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerMode"></a>

```go
func ResetPoolerMode()
```

##### `ResetRegionId` <a name="ResetRegionId" id="@cdktf/provider-neon.endpoint.Endpoint.resetRegionId"></a>

```go
func ResetRegionId()
```

##### `ResetSuspendTimeoutSeconds` <a name="ResetSuspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.Endpoint.resetSuspendTimeoutSeconds"></a>

```go
func ResetSuspendTimeoutSeconds()
```

##### `ResetType` <a name="ResetType" id="@cdktf/provider-neon.endpoint.Endpoint.resetType"></a>

```go
func ResetType()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTF code for importing a Endpoint resource upon running "cdktf plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktf/provider-neon.endpoint.Endpoint.isConstruct"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/endpoint"

endpoint.Endpoint_IsConstruct(x interface{}) *bool
```

Checks if `x` is a construct.

Use this method instead of `instanceof` to properly detect `Construct`
instances, even when the construct library is symlinked.

Explanation: in JavaScript, multiple copies of the `constructs` library on
disk are seen as independent, completely different libraries. As a
consequence, the class `Construct` in each copy of the `constructs` library
is seen as a different class, and an instance of one class will not test as
`instanceof` the other class. `npm install` will not create installations
like this, but users may manually symlink construct libraries together or
use a monorepo tool: in those cases, multiple copies of the `constructs`
library can be accidentally installed, and `instanceof` will behave
unpredictably. It is safest to avoid using `instanceof`, and using
this type-testing method instead.

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/endpoint"

endpoint.Endpoint_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/endpoint"

endpoint.Endpoint_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/endpoint"

endpoint.Endpoint_GenerateConfigForImport(scope Construct, importToId *string, importFromId *string, provider TerraformProvider) ImportableResource
```

Generates CDKTF code for importing a Endpoint resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importToId"></a>

- *Type:* *string

The construct id used in the generated config for the Endpoint to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importFromId"></a>

- *Type:* *string

The id of the existing Endpoint that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.provider"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

? Optional instance of the provider where the Endpoint to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.host">Host</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost">ProxyHost</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput">AutoscalingLimitMaxCuInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput">AutoscalingLimitMinCuInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput">BranchIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput">ComputeProvisionerInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput">DisabledInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput">PgSettingsInput</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput">PoolerEnabledInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput">PoolerModeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput">ProjectIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput">RegionIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput">SuspendTimeoutSecondsInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.typeInput">TypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu">AutoscalingLimitMaxCu</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu">AutoscalingLimitMinCu</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchId">BranchId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner">ComputeProvisioner</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabled">Disabled</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings">PgSettings</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled">PoolerEnabled</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode">PoolerMode</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectId">ProjectId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionId">RegionId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds">SuspendTimeoutSeconds</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.type">Type</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-neon.endpoint.Endpoint.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.endpoint.Endpoint.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-neon.endpoint.Endpoint.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-neon.endpoint.Endpoint.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-neon.endpoint.Endpoint.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.endpoint.Endpoint.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-neon.endpoint.Endpoint.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Host`<sup>Required</sup> <a name="Host" id="@cdktf/provider-neon.endpoint.Endpoint.property.host"></a>

```go
func Host() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.endpoint.Endpoint.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `ProxyHost`<sup>Required</sup> <a name="ProxyHost" id="@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost"></a>

```go
func ProxyHost() *string
```

- *Type:* *string

---

##### `AutoscalingLimitMaxCuInput`<sup>Optional</sup> <a name="AutoscalingLimitMaxCuInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput"></a>

```go
func AutoscalingLimitMaxCuInput() *f64
```

- *Type:* *f64

---

##### `AutoscalingLimitMinCuInput`<sup>Optional</sup> <a name="AutoscalingLimitMinCuInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput"></a>

```go
func AutoscalingLimitMinCuInput() *f64
```

- *Type:* *f64

---

##### `BranchIdInput`<sup>Optional</sup> <a name="BranchIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput"></a>

```go
func BranchIdInput() *string
```

- *Type:* *string

---

##### `ComputeProvisionerInput`<sup>Optional</sup> <a name="ComputeProvisionerInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput"></a>

```go
func ComputeProvisionerInput() *string
```

- *Type:* *string

---

##### `DisabledInput`<sup>Optional</sup> <a name="DisabledInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput"></a>

```go
func DisabledInput() interface{}
```

- *Type:* interface{}

---

##### `PgSettingsInput`<sup>Optional</sup> <a name="PgSettingsInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput"></a>

```go
func PgSettingsInput() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `PoolerEnabledInput`<sup>Optional</sup> <a name="PoolerEnabledInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput"></a>

```go
func PoolerEnabledInput() interface{}
```

- *Type:* interface{}

---

##### `PoolerModeInput`<sup>Optional</sup> <a name="PoolerModeInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput"></a>

```go
func PoolerModeInput() *string
```

- *Type:* *string

---

##### `ProjectIdInput`<sup>Optional</sup> <a name="ProjectIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput"></a>

```go
func ProjectIdInput() *string
```

- *Type:* *string

---

##### `RegionIdInput`<sup>Optional</sup> <a name="RegionIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput"></a>

```go
func RegionIdInput() *string
```

- *Type:* *string

---

##### `SuspendTimeoutSecondsInput`<sup>Optional</sup> <a name="SuspendTimeoutSecondsInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput"></a>

```go
func SuspendTimeoutSecondsInput() *f64
```

- *Type:* *f64

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.typeInput"></a>

```go
func TypeInput() *string
```

- *Type:* *string

---

##### `AutoscalingLimitMaxCu`<sup>Required</sup> <a name="AutoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu"></a>

```go
func AutoscalingLimitMaxCu() *f64
```

- *Type:* *f64

---

##### `AutoscalingLimitMinCu`<sup>Required</sup> <a name="AutoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu"></a>

```go
func AutoscalingLimitMinCu() *f64
```

- *Type:* *f64

---

##### `BranchId`<sup>Required</sup> <a name="BranchId" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchId"></a>

```go
func BranchId() *string
```

- *Type:* *string

---

##### `ComputeProvisioner`<sup>Required</sup> <a name="ComputeProvisioner" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner"></a>

```go
func ComputeProvisioner() *string
```

- *Type:* *string

---

##### `Disabled`<sup>Required</sup> <a name="Disabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabled"></a>

```go
func Disabled() interface{}
```

- *Type:* interface{}

---

##### `PgSettings`<sup>Required</sup> <a name="PgSettings" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings"></a>

```go
func PgSettings() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `PoolerEnabled`<sup>Required</sup> <a name="PoolerEnabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled"></a>

```go
func PoolerEnabled() interface{}
```

- *Type:* interface{}

---

##### `PoolerMode`<sup>Required</sup> <a name="PoolerMode" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode"></a>

```go
func PoolerMode() *string
```

- *Type:* *string

---

##### `ProjectId`<sup>Required</sup> <a name="ProjectId" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectId"></a>

```go
func ProjectId() *string
```

- *Type:* *string

---

##### `RegionId`<sup>Required</sup> <a name="RegionId" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionId"></a>

```go
func RegionId() *string
```

- *Type:* *string

---

##### `SuspendTimeoutSeconds`<sup>Required</sup> <a name="SuspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds"></a>

```go
func SuspendTimeoutSeconds() *f64
```

- *Type:* *f64

---

##### `Type`<sup>Required</sup> <a name="Type" id="@cdktf/provider-neon.endpoint.Endpoint.property.type"></a>

```go
func Type() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### EndpointConfig <a name="EndpointConfig" id="@cdktf/provider-neon.endpoint.EndpointConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.endpoint.EndpointConfig.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/endpoint"

&endpoint.EndpointConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	BranchId: *string,
	ProjectId: *string,
	AutoscalingLimitMaxCu: *f64,
	AutoscalingLimitMinCu: *f64,
	ComputeProvisioner: *string,
	Disabled: interface{},
	PgSettings: *map[string]*string,
	PoolerEnabled: interface{},
	PoolerMode: *string,
	RegionId: *string,
	SuspendTimeoutSeconds: *f64,
	Type: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId">BranchId</a></code> | <code>*string</code> | Branch ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId">ProjectId</a></code> | <code>*string</code> | Project ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu">AutoscalingLimitMaxCu</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu">AutoscalingLimitMinCu</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner">ComputeProvisioner</a></code> | <code>*string</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled">Disabled</a></code> | <code>interface{}</code> | Disable the endpoint. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings">PgSettings</a></code> | <code>*map[string]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled">PoolerEnabled</a></code> | <code>interface{}</code> | Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode">PoolerMode</a></code> | <code>*string</code> | Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId">RegionId</a></code> | <code>*string</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds">SuspendTimeoutSeconds</a></code> | <code>*f64</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.type">Type</a></code> | <code>*string</code> | Access type. **Note** that "read_write" is the only supported type yet. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `BranchId`<sup>Required</sup> <a name="BranchId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId"></a>

```go
BranchId *string
```

- *Type:* *string

Branch ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#branch_id Endpoint#branch_id}

---

##### `ProjectId`<sup>Required</sup> <a name="ProjectId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId"></a>

```go
ProjectId *string
```

- *Type:* *string

Project ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#project_id Endpoint#project_id}

---

##### `AutoscalingLimitMaxCu`<sup>Optional</sup> <a name="AutoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu"></a>

```go
AutoscalingLimitMaxCu *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}.

---

##### `AutoscalingLimitMinCu`<sup>Optional</sup> <a name="AutoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu"></a>

```go
AutoscalingLimitMinCu *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}.

---

##### `ComputeProvisioner`<sup>Optional</sup> <a name="ComputeProvisioner" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner"></a>

```go
ComputeProvisioner *string
```

- *Type:* *string

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#compute_provisioner Endpoint#compute_provisioner}

---

##### `Disabled`<sup>Optional</sup> <a name="Disabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled"></a>

```go
Disabled interface{}
```

- *Type:* interface{}

Disable the endpoint.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#disabled Endpoint#disabled}

---

##### `PgSettings`<sup>Optional</sup> <a name="PgSettings" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings"></a>

```go
PgSettings *map[string]*string
```

- *Type:* *map[string]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}.

---

##### `PoolerEnabled`<sup>Optional</sup> <a name="PoolerEnabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled"></a>

```go
PoolerEnabled interface{}
```

- *Type:* interface{}

Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_enabled Endpoint#pooler_enabled}

---

##### `PoolerMode`<sup>Optional</sup> <a name="PoolerMode" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode"></a>

```go
PoolerMode *string
```

- *Type:* *string

Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_mode Endpoint#pooler_mode}

---

##### `RegionId`<sup>Optional</sup> <a name="RegionId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId"></a>

```go
RegionId *string
```

- *Type:* *string

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#region_id Endpoint#region_id}

---

##### `SuspendTimeoutSeconds`<sup>Optional</sup> <a name="SuspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds"></a>

```go
SuspendTimeoutSeconds *f64
```

- *Type:* *f64

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#suspend_timeout_seconds Endpoint#suspend_timeout_seconds}

---

##### `Type`<sup>Optional</sup> <a name="Type" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.type"></a>

```go
Type *string
```

- *Type:* *string

Access type. **Note** that "read_write" is the only supported type yet.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#type Endpoint#type}

---



