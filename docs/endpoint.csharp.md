# `neon_endpoint`

Refer to the Terraform Registory for docs: [`neon_endpoint`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint).

# `endpoint` Submodule <a name="`endpoint` Submodule" id="@cdktf/provider-neon.endpoint"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Endpoint <a name="Endpoint" id="@cdktf/provider-neon.endpoint.Endpoint"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint neon_endpoint}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new Endpoint(Construct Scope, string Id, EndpointConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig">EndpointConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.config"></a>

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

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-neon.endpoint.Endpoint.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-neon.endpoint.Endpoint.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget"></a>

```csharp
private void AddMoveTarget(string MoveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `ImportFrom` <a name="ImportFrom" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom"></a>

```csharp
private void ImportFrom(string Id, TerraformProvider Provider = null)
```

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.id"></a>

- *Type:* string

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.provider"></a>

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `MoveTo` <a name="MoveTo" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo"></a>

```csharp
private void MoveTo(string MoveTarget, object Index = null)
```

Moves this resource to the target resource given by moveTarget.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `Index`<sup>Optional</sup> <a name="Index" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.index"></a>

- *Type:* object

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `ResetAutoscalingLimitMaxCu` <a name="ResetAutoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMaxCu"></a>

```csharp
private void ResetAutoscalingLimitMaxCu()
```

##### `ResetAutoscalingLimitMinCu` <a name="ResetAutoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMinCu"></a>

```csharp
private void ResetAutoscalingLimitMinCu()
```

##### `ResetComputeProvisioner` <a name="ResetComputeProvisioner" id="@cdktf/provider-neon.endpoint.Endpoint.resetComputeProvisioner"></a>

```csharp
private void ResetComputeProvisioner()
```

##### `ResetDisabled` <a name="ResetDisabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetDisabled"></a>

```csharp
private void ResetDisabled()
```

##### `ResetPgSettings` <a name="ResetPgSettings" id="@cdktf/provider-neon.endpoint.Endpoint.resetPgSettings"></a>

```csharp
private void ResetPgSettings()
```

##### `ResetPoolerEnabled` <a name="ResetPoolerEnabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerEnabled"></a>

```csharp
private void ResetPoolerEnabled()
```

##### `ResetPoolerMode` <a name="ResetPoolerMode" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerMode"></a>

```csharp
private void ResetPoolerMode()
```

##### `ResetRegionId` <a name="ResetRegionId" id="@cdktf/provider-neon.endpoint.Endpoint.resetRegionId"></a>

```csharp
private void ResetRegionId()
```

##### `ResetSuspendTimeoutSeconds` <a name="ResetSuspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.Endpoint.resetSuspendTimeoutSeconds"></a>

```csharp
private void ResetSuspendTimeoutSeconds()
```

##### `ResetType` <a name="ResetType" id="@cdktf/provider-neon.endpoint.Endpoint.resetType"></a>

```csharp
private void ResetType()
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

```csharp
using HashiCorp.Cdktf.Providers.Neon;

Endpoint.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-neon.endpoint.Endpoint.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

Endpoint.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

Endpoint.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

Endpoint.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTF code for importing a Endpoint resource upon running "cdktf plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Endpoint to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Endpoint that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.provider"></a>

- *Type:* HashiCorp.Cdktf.TerraformProvider

? Optional instance of the provider where the Endpoint to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack">CdktfStack</a></code> | <code>HashiCorp.Cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>HashiCorp.Cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.host">Host</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost">ProxyHost</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput">AutoscalingLimitMaxCuInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput">AutoscalingLimitMinCuInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput">BranchIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput">ComputeProvisionerInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput">DisabledInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput">PgSettingsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput">PoolerEnabledInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput">PoolerModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput">ProjectIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput">RegionIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput">SuspendTimeoutSecondsInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu">AutoscalingLimitMaxCu</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu">AutoscalingLimitMinCu</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchId">BranchId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner">ComputeProvisioner</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabled">Disabled</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings">PgSettings</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled">PoolerEnabled</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode">PoolerMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectId">ProjectId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionId">RegionId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds">SuspendTimeoutSeconds</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.type">Type</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-neon.endpoint.Endpoint.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.endpoint.Endpoint.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-neon.endpoint.Endpoint.property.connection"></a>

```csharp
public object Connection { get; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-neon.endpoint.Endpoint.property.count"></a>

```csharp
public object Count { get; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-neon.endpoint.Endpoint.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.endpoint.Endpoint.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-neon.endpoint.Endpoint.property.provisioners"></a>

```csharp
public object[] Provisioners { get; }
```

- *Type:* object[]

---

##### `Host`<sup>Required</sup> <a name="Host" id="@cdktf/provider-neon.endpoint.Endpoint.property.host"></a>

```csharp
public string Host { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.endpoint.Endpoint.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `ProxyHost`<sup>Required</sup> <a name="ProxyHost" id="@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost"></a>

```csharp
public string ProxyHost { get; }
```

- *Type:* string

---

##### `AutoscalingLimitMaxCuInput`<sup>Optional</sup> <a name="AutoscalingLimitMaxCuInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput"></a>

```csharp
public double AutoscalingLimitMaxCuInput { get; }
```

- *Type:* double

---

##### `AutoscalingLimitMinCuInput`<sup>Optional</sup> <a name="AutoscalingLimitMinCuInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput"></a>

```csharp
public double AutoscalingLimitMinCuInput { get; }
```

- *Type:* double

---

##### `BranchIdInput`<sup>Optional</sup> <a name="BranchIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput"></a>

```csharp
public string BranchIdInput { get; }
```

- *Type:* string

---

##### `ComputeProvisionerInput`<sup>Optional</sup> <a name="ComputeProvisionerInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput"></a>

```csharp
public string ComputeProvisionerInput { get; }
```

- *Type:* string

---

##### `DisabledInput`<sup>Optional</sup> <a name="DisabledInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput"></a>

```csharp
public object DisabledInput { get; }
```

- *Type:* object

---

##### `PgSettingsInput`<sup>Optional</sup> <a name="PgSettingsInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> PgSettingsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `PoolerEnabledInput`<sup>Optional</sup> <a name="PoolerEnabledInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput"></a>

```csharp
public object PoolerEnabledInput { get; }
```

- *Type:* object

---

##### `PoolerModeInput`<sup>Optional</sup> <a name="PoolerModeInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput"></a>

```csharp
public string PoolerModeInput { get; }
```

- *Type:* string

---

##### `ProjectIdInput`<sup>Optional</sup> <a name="ProjectIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput"></a>

```csharp
public string ProjectIdInput { get; }
```

- *Type:* string

---

##### `RegionIdInput`<sup>Optional</sup> <a name="RegionIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput"></a>

```csharp
public string RegionIdInput { get; }
```

- *Type:* string

---

##### `SuspendTimeoutSecondsInput`<sup>Optional</sup> <a name="SuspendTimeoutSecondsInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput"></a>

```csharp
public double SuspendTimeoutSecondsInput { get; }
```

- *Type:* double

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `AutoscalingLimitMaxCu`<sup>Required</sup> <a name="AutoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu"></a>

```csharp
public double AutoscalingLimitMaxCu { get; }
```

- *Type:* double

---

##### `AutoscalingLimitMinCu`<sup>Required</sup> <a name="AutoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu"></a>

```csharp
public double AutoscalingLimitMinCu { get; }
```

- *Type:* double

---

##### `BranchId`<sup>Required</sup> <a name="BranchId" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchId"></a>

```csharp
public string BranchId { get; }
```

- *Type:* string

---

##### `ComputeProvisioner`<sup>Required</sup> <a name="ComputeProvisioner" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner"></a>

```csharp
public string ComputeProvisioner { get; }
```

- *Type:* string

---

##### `Disabled`<sup>Required</sup> <a name="Disabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabled"></a>

```csharp
public object Disabled { get; }
```

- *Type:* object

---

##### `PgSettings`<sup>Required</sup> <a name="PgSettings" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> PgSettings { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `PoolerEnabled`<sup>Required</sup> <a name="PoolerEnabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled"></a>

```csharp
public object PoolerEnabled { get; }
```

- *Type:* object

---

##### `PoolerMode`<sup>Required</sup> <a name="PoolerMode" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode"></a>

```csharp
public string PoolerMode { get; }
```

- *Type:* string

---

##### `ProjectId`<sup>Required</sup> <a name="ProjectId" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectId"></a>

```csharp
public string ProjectId { get; }
```

- *Type:* string

---

##### `RegionId`<sup>Required</sup> <a name="RegionId" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionId"></a>

```csharp
public string RegionId { get; }
```

- *Type:* string

---

##### `SuspendTimeoutSeconds`<sup>Required</sup> <a name="SuspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds"></a>

```csharp
public double SuspendTimeoutSeconds { get; }
```

- *Type:* double

---

##### `Type`<sup>Required</sup> <a name="Type" id="@cdktf/provider-neon.endpoint.Endpoint.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### EndpointConfig <a name="EndpointConfig" id="@cdktf/provider-neon.endpoint.EndpointConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.endpoint.EndpointConfig.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new EndpointConfig {
    object Connection = null,
    object Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    object[] Provisioners = null,
    string BranchId,
    string ProjectId,
    double AutoscalingLimitMaxCu = null,
    double AutoscalingLimitMinCu = null,
    string ComputeProvisioner = null,
    object Disabled = null,
    System.Collections.Generic.IDictionary<string, string> PgSettings = null,
    object PoolerEnabled = null,
    string PoolerMode = null,
    string RegionId = null,
    double SuspendTimeoutSeconds = null,
    string Type = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn">DependsOn</a></code> | <code>HashiCorp.Cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId">BranchId</a></code> | <code>string</code> | Branch ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId">ProjectId</a></code> | <code>string</code> | Project ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu">AutoscalingLimitMaxCu</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu">AutoscalingLimitMinCu</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner">ComputeProvisioner</a></code> | <code>string</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled">Disabled</a></code> | <code>object</code> | Disable the endpoint. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings">PgSettings</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled">PoolerEnabled</a></code> | <code>object</code> | Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode">PoolerMode</a></code> | <code>string</code> | Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId">RegionId</a></code> | <code>string</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds">SuspendTimeoutSeconds</a></code> | <code>double</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.type">Type</a></code> | <code>string</code> | Access type. **Note** that "read_write" is the only supported type yet. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.connection"></a>

```csharp
public object Connection { get; set; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.count"></a>

```csharp
public object Count { get; set; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners"></a>

```csharp
public object[] Provisioners { get; set; }
```

- *Type:* object[]

---

##### `BranchId`<sup>Required</sup> <a name="BranchId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId"></a>

```csharp
public string BranchId { get; set; }
```

- *Type:* string

Branch ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#branch_id Endpoint#branch_id}

---

##### `ProjectId`<sup>Required</sup> <a name="ProjectId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId"></a>

```csharp
public string ProjectId { get; set; }
```

- *Type:* string

Project ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#project_id Endpoint#project_id}

---

##### `AutoscalingLimitMaxCu`<sup>Optional</sup> <a name="AutoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu"></a>

```csharp
public double AutoscalingLimitMaxCu { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}.

---

##### `AutoscalingLimitMinCu`<sup>Optional</sup> <a name="AutoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu"></a>

```csharp
public double AutoscalingLimitMinCu { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}.

---

##### `ComputeProvisioner`<sup>Optional</sup> <a name="ComputeProvisioner" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner"></a>

```csharp
public string ComputeProvisioner { get; set; }
```

- *Type:* string

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#compute_provisioner Endpoint#compute_provisioner}

---

##### `Disabled`<sup>Optional</sup> <a name="Disabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled"></a>

```csharp
public object Disabled { get; set; }
```

- *Type:* object

Disable the endpoint.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#disabled Endpoint#disabled}

---

##### `PgSettings`<sup>Optional</sup> <a name="PgSettings" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> PgSettings { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}.

---

##### `PoolerEnabled`<sup>Optional</sup> <a name="PoolerEnabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled"></a>

```csharp
public object PoolerEnabled { get; set; }
```

- *Type:* object

Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_enabled Endpoint#pooler_enabled}

---

##### `PoolerMode`<sup>Optional</sup> <a name="PoolerMode" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode"></a>

```csharp
public string PoolerMode { get; set; }
```

- *Type:* string

Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_mode Endpoint#pooler_mode}

---

##### `RegionId`<sup>Optional</sup> <a name="RegionId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId"></a>

```csharp
public string RegionId { get; set; }
```

- *Type:* string

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#region_id Endpoint#region_id}

---

##### `SuspendTimeoutSeconds`<sup>Optional</sup> <a name="SuspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds"></a>

```csharp
public double SuspendTimeoutSeconds { get; set; }
```

- *Type:* double

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#suspend_timeout_seconds Endpoint#suspend_timeout_seconds}

---

##### `Type`<sup>Optional</sup> <a name="Type" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

Access type. **Note** that "read_write" is the only supported type yet.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#type Endpoint#type}

---



