# `neon_project`

Refer to the Terraform Registory for docs: [`neon_project`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project).

# `project` Submodule <a name="`project` Submodule" id="@cdktf/provider-neon.project"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Project <a name="Project" id="@cdktf/provider-neon.project.Project"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project neon_project}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.Project.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new Project(Construct Scope, string Id, ProjectConfig Config = null);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectConfig">ProjectConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktf/provider-neon.project.Project.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.project.Project.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Optional</sup> <a name="Config" id="@cdktf/provider-neon.project.Project.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectConfig">ProjectConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-neon.project.Project.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-neon.project.Project.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-neon.project.Project.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktf/provider-neon.project.Project.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktf/provider-neon.project.Project.putBranch">PutBranch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.putDefaultEndpointSettings">PutDefaultEndpointSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.putQuota">PutQuota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetBranch">ResetBranch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetComputeProvisioner">ResetComputeProvisioner</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetDefaultEndpointSettings">ResetDefaultEndpointSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetHistoryRetentionSeconds">ResetHistoryRetentionSeconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetName">ResetName</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetPgVersion">ResetPgVersion</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetQuota">ResetQuota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetRegionId">ResetRegionId</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetStorePassword">ResetStorePassword</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktf/provider-neon.project.Project.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-neon.project.Project.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktf/provider-neon.project.Project.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktf/provider-neon.project.Project.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-neon.project.Project.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktf/provider-neon.project.Project.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-neon.project.Project.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-neon.project.Project.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-neon.project.Project.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktf/provider-neon.project.Project.addMoveTarget"></a>

```csharp
private void AddMoveTarget(string MoveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktf/provider-neon.project.Project.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.project.Project.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.project.Project.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `ImportFrom` <a name="ImportFrom" id="@cdktf/provider-neon.project.Project.importFrom"></a>

```csharp
private void ImportFrom(string Id, TerraformProvider Provider = null)
```

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.project.Project.importFrom.parameter.id"></a>

- *Type:* string

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.project.Project.importFrom.parameter.provider"></a>

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `MoveTo` <a name="MoveTo" id="@cdktf/provider-neon.project.Project.moveTo"></a>

```csharp
private void MoveTo(string MoveTarget, object Index = null)
```

Moves this resource to the target resource given by moveTarget.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktf/provider-neon.project.Project.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `Index`<sup>Optional</sup> <a name="Index" id="@cdktf/provider-neon.project.Project.moveTo.parameter.index"></a>

- *Type:* object

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `PutBranch` <a name="PutBranch" id="@cdktf/provider-neon.project.Project.putBranch"></a>

```csharp
private void PutBranch(ProjectBranch Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktf/provider-neon.project.Project.putBranch.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---

##### `PutDefaultEndpointSettings` <a name="PutDefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings"></a>

```csharp
private void PutDefaultEndpointSettings(ProjectDefaultEndpointSettings Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---

##### `PutQuota` <a name="PutQuota" id="@cdktf/provider-neon.project.Project.putQuota"></a>

```csharp
private void PutQuota(ProjectQuota Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktf/provider-neon.project.Project.putQuota.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---

##### `ResetBranch` <a name="ResetBranch" id="@cdktf/provider-neon.project.Project.resetBranch"></a>

```csharp
private void ResetBranch()
```

##### `ResetComputeProvisioner` <a name="ResetComputeProvisioner" id="@cdktf/provider-neon.project.Project.resetComputeProvisioner"></a>

```csharp
private void ResetComputeProvisioner()
```

##### `ResetDefaultEndpointSettings` <a name="ResetDefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.resetDefaultEndpointSettings"></a>

```csharp
private void ResetDefaultEndpointSettings()
```

##### `ResetHistoryRetentionSeconds` <a name="ResetHistoryRetentionSeconds" id="@cdktf/provider-neon.project.Project.resetHistoryRetentionSeconds"></a>

```csharp
private void ResetHistoryRetentionSeconds()
```

##### `ResetName` <a name="ResetName" id="@cdktf/provider-neon.project.Project.resetName"></a>

```csharp
private void ResetName()
```

##### `ResetPgVersion` <a name="ResetPgVersion" id="@cdktf/provider-neon.project.Project.resetPgVersion"></a>

```csharp
private void ResetPgVersion()
```

##### `ResetQuota` <a name="ResetQuota" id="@cdktf/provider-neon.project.Project.resetQuota"></a>

```csharp
private void ResetQuota()
```

##### `ResetRegionId` <a name="ResetRegionId" id="@cdktf/provider-neon.project.Project.resetRegionId"></a>

```csharp
private void ResetRegionId()
```

##### `ResetStorePassword` <a name="ResetStorePassword" id="@cdktf/provider-neon.project.Project.resetStorePassword"></a>

```csharp
private void ResetStorePassword()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTF code for importing a Project resource upon running "cdktf plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktf/provider-neon.project.Project.isConstruct"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

Project.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-neon.project.Project.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-neon.project.Project.isTerraformElement"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

Project.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-neon.project.Project.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktf/provider-neon.project.Project.isTerraformResource"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

Project.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktf/provider-neon.project.Project.isTerraformResource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktf/provider-neon.project.Project.generateConfigForImport"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

Project.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTF code for importing a Project resource upon running "cdktf plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Project to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Project that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.provider"></a>

- *Type:* HashiCorp.Cdktf.TerraformProvider

? Optional instance of the provider where the Project to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-neon.project.Project.property.cdktfStack">CdktfStack</a></code> | <code>HashiCorp.Cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>HashiCorp.Cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branch">Branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connectionUri">ConnectionUri</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseHost">DatabaseHost</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseName">DatabaseName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databasePassword">DatabasePassword</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseUser">DatabaseUser</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultBranchId">DefaultBranchId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettings">DefaultEndpointSettings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quota">Quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branchInput">BranchInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisionerInput">ComputeProvisionerInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput">DefaultEndpointSettingsInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput">HistoryRetentionSecondsInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersionInput">PgVersionInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quotaInput">QuotaInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionIdInput">RegionIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePasswordInput">StorePasswordInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisioner">ComputeProvisioner</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSeconds">HistoryRetentionSeconds</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersion">PgVersion</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionId">RegionId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePassword">StorePassword</a></code> | <code>object</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-neon.project.Project.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-neon.project.Project.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.project.Project.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-neon.project.Project.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-neon.project.Project.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-neon.project.Project.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-neon.project.Project.property.connection"></a>

```csharp
public object Connection { get; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-neon.project.Project.property.count"></a>

```csharp
public object Count { get; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-neon.project.Project.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-neon.project.Project.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-neon.project.Project.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.project.Project.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-neon.project.Project.property.provisioners"></a>

```csharp
public object[] Provisioners { get; }
```

- *Type:* object[]

---

##### `Branch`<sup>Required</sup> <a name="Branch" id="@cdktf/provider-neon.project.Project.property.branch"></a>

```csharp
public ProjectBranchOutputReference Branch { get; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a>

---

##### `ConnectionUri`<sup>Required</sup> <a name="ConnectionUri" id="@cdktf/provider-neon.project.Project.property.connectionUri"></a>

```csharp
public string ConnectionUri { get; }
```

- *Type:* string

---

##### `DatabaseHost`<sup>Required</sup> <a name="DatabaseHost" id="@cdktf/provider-neon.project.Project.property.databaseHost"></a>

```csharp
public string DatabaseHost { get; }
```

- *Type:* string

---

##### `DatabaseName`<sup>Required</sup> <a name="DatabaseName" id="@cdktf/provider-neon.project.Project.property.databaseName"></a>

```csharp
public string DatabaseName { get; }
```

- *Type:* string

---

##### `DatabasePassword`<sup>Required</sup> <a name="DatabasePassword" id="@cdktf/provider-neon.project.Project.property.databasePassword"></a>

```csharp
public string DatabasePassword { get; }
```

- *Type:* string

---

##### `DatabaseUser`<sup>Required</sup> <a name="DatabaseUser" id="@cdktf/provider-neon.project.Project.property.databaseUser"></a>

```csharp
public string DatabaseUser { get; }
```

- *Type:* string

---

##### `DefaultBranchId`<sup>Required</sup> <a name="DefaultBranchId" id="@cdktf/provider-neon.project.Project.property.defaultBranchId"></a>

```csharp
public string DefaultBranchId { get; }
```

- *Type:* string

---

##### `DefaultEndpointSettings`<sup>Required</sup> <a name="DefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettings"></a>

```csharp
public ProjectDefaultEndpointSettingsOutputReference DefaultEndpointSettings { get; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a>

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.project.Project.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Quota`<sup>Required</sup> <a name="Quota" id="@cdktf/provider-neon.project.Project.property.quota"></a>

```csharp
public ProjectQuotaOutputReference Quota { get; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a>

---

##### `BranchInput`<sup>Optional</sup> <a name="BranchInput" id="@cdktf/provider-neon.project.Project.property.branchInput"></a>

```csharp
public ProjectBranch BranchInput { get; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---

##### `ComputeProvisionerInput`<sup>Optional</sup> <a name="ComputeProvisionerInput" id="@cdktf/provider-neon.project.Project.property.computeProvisionerInput"></a>

```csharp
public string ComputeProvisionerInput { get; }
```

- *Type:* string

---

##### `DefaultEndpointSettingsInput`<sup>Optional</sup> <a name="DefaultEndpointSettingsInput" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput"></a>

```csharp
public ProjectDefaultEndpointSettings DefaultEndpointSettingsInput { get; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---

##### `HistoryRetentionSecondsInput`<sup>Optional</sup> <a name="HistoryRetentionSecondsInput" id="@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput"></a>

```csharp
public double HistoryRetentionSecondsInput { get; }
```

- *Type:* double

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktf/provider-neon.project.Project.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `PgVersionInput`<sup>Optional</sup> <a name="PgVersionInput" id="@cdktf/provider-neon.project.Project.property.pgVersionInput"></a>

```csharp
public double PgVersionInput { get; }
```

- *Type:* double

---

##### `QuotaInput`<sup>Optional</sup> <a name="QuotaInput" id="@cdktf/provider-neon.project.Project.property.quotaInput"></a>

```csharp
public ProjectQuota QuotaInput { get; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---

##### `RegionIdInput`<sup>Optional</sup> <a name="RegionIdInput" id="@cdktf/provider-neon.project.Project.property.regionIdInput"></a>

```csharp
public string RegionIdInput { get; }
```

- *Type:* string

---

##### `StorePasswordInput`<sup>Optional</sup> <a name="StorePasswordInput" id="@cdktf/provider-neon.project.Project.property.storePasswordInput"></a>

```csharp
public object StorePasswordInput { get; }
```

- *Type:* object

---

##### `ComputeProvisioner`<sup>Required</sup> <a name="ComputeProvisioner" id="@cdktf/provider-neon.project.Project.property.computeProvisioner"></a>

```csharp
public string ComputeProvisioner { get; }
```

- *Type:* string

---

##### `HistoryRetentionSeconds`<sup>Required</sup> <a name="HistoryRetentionSeconds" id="@cdktf/provider-neon.project.Project.property.historyRetentionSeconds"></a>

```csharp
public double HistoryRetentionSeconds { get; }
```

- *Type:* double

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktf/provider-neon.project.Project.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `PgVersion`<sup>Required</sup> <a name="PgVersion" id="@cdktf/provider-neon.project.Project.property.pgVersion"></a>

```csharp
public double PgVersion { get; }
```

- *Type:* double

---

##### `RegionId`<sup>Required</sup> <a name="RegionId" id="@cdktf/provider-neon.project.Project.property.regionId"></a>

```csharp
public string RegionId { get; }
```

- *Type:* string

---

##### `StorePassword`<sup>Required</sup> <a name="StorePassword" id="@cdktf/provider-neon.project.Project.property.storePassword"></a>

```csharp
public object StorePassword { get; }
```

- *Type:* object

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-neon.project.Project.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ProjectBranch <a name="ProjectBranch" id="@cdktf/provider-neon.project.ProjectBranch"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectBranch.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new ProjectBranch {
    string DatabaseName = null,
    string Name = null,
    string RoleName = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.databaseName">DatabaseName</a></code> | <code>string</code> | The database name. If not specified, the default database name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.name">Name</a></code> | <code>string</code> | The branch name. If not specified, the default branch name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.roleName">RoleName</a></code> | <code>string</code> | The role name. If not specified, the default role name will be used. |

---

##### `DatabaseName`<sup>Optional</sup> <a name="DatabaseName" id="@cdktf/provider-neon.project.ProjectBranch.property.databaseName"></a>

```csharp
public string DatabaseName { get; set; }
```

- *Type:* string

The database name. If not specified, the default database name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#database_name Project#database_name}

---

##### `Name`<sup>Optional</sup> <a name="Name" id="@cdktf/provider-neon.project.ProjectBranch.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

The branch name. If not specified, the default branch name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `RoleName`<sup>Optional</sup> <a name="RoleName" id="@cdktf/provider-neon.project.ProjectBranch.property.roleName"></a>

```csharp
public string RoleName { get; set; }
```

- *Type:* string

The role name. If not specified, the default role name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#role_name Project#role_name}

---

### ProjectConfig <a name="ProjectConfig" id="@cdktf/provider-neon.project.ProjectConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectConfig.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new ProjectConfig {
    object Connection = null,
    object Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    object[] Provisioners = null,
    ProjectBranch Branch = null,
    string ComputeProvisioner = null,
    ProjectDefaultEndpointSettings DefaultEndpointSettings = null,
    double HistoryRetentionSeconds = null,
    string Name = null,
    double PgVersion = null,
    ProjectQuota Quota = null,
    string RegionId = null,
    object StorePassword = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.dependsOn">DependsOn</a></code> | <code>HashiCorp.Cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.branch">Branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | branch block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner">ComputeProvisioner</a></code> | <code>string</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings">DefaultEndpointSettings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | default_endpoint_settings block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds">HistoryRetentionSeconds</a></code> | <code>double</code> | The number of seconds to retain the point-in-time restore (PITR) backup history for this project. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.name">Name</a></code> | <code>string</code> | Project name. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.pgVersion">PgVersion</a></code> | <code>double</code> | Postgres version. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.quota">Quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | quota block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.regionId">RegionId</a></code> | <code>string</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.storePassword">StorePassword</a></code> | <code>object</code> | Whether or not passwords are stored for roles in the Neon project. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-neon.project.ProjectConfig.property.connection"></a>

```csharp
public object Connection { get; set; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-neon.project.ProjectConfig.property.count"></a>

```csharp
public object Count { get; set; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-neon.project.ProjectConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-neon.project.ProjectConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-neon.project.ProjectConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.project.ProjectConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-neon.project.ProjectConfig.property.provisioners"></a>

```csharp
public object[] Provisioners { get; set; }
```

- *Type:* object[]

---

##### `Branch`<sup>Optional</sup> <a name="Branch" id="@cdktf/provider-neon.project.ProjectConfig.property.branch"></a>

```csharp
public ProjectBranch Branch { get; set; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

branch block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#branch Project#branch}

---

##### `ComputeProvisioner`<sup>Optional</sup> <a name="ComputeProvisioner" id="@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner"></a>

```csharp
public string ComputeProvisioner { get; set; }
```

- *Type:* string

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_provisioner Project#compute_provisioner}

---

##### `DefaultEndpointSettings`<sup>Optional</sup> <a name="DefaultEndpointSettings" id="@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings"></a>

```csharp
public ProjectDefaultEndpointSettings DefaultEndpointSettings { get; set; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

default_endpoint_settings block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#default_endpoint_settings Project#default_endpoint_settings}

---

##### `HistoryRetentionSeconds`<sup>Optional</sup> <a name="HistoryRetentionSeconds" id="@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds"></a>

```csharp
public double HistoryRetentionSeconds { get; set; }
```

- *Type:* double

The number of seconds to retain the point-in-time restore (PITR) backup history for this project.

Default: 7 days, see https://neon.tech/docs/reference/glossary#point-in-time-restore.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#history_retention_seconds Project#history_retention_seconds}

---

##### `Name`<sup>Optional</sup> <a name="Name" id="@cdktf/provider-neon.project.ProjectConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

Project name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `PgVersion`<sup>Optional</sup> <a name="PgVersion" id="@cdktf/provider-neon.project.ProjectConfig.property.pgVersion"></a>

```csharp
public double PgVersion { get; set; }
```

- *Type:* double

Postgres version.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#pg_version Project#pg_version}

---

##### `Quota`<sup>Optional</sup> <a name="Quota" id="@cdktf/provider-neon.project.ProjectConfig.property.quota"></a>

```csharp
public ProjectQuota Quota { get; set; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

quota block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#quota Project#quota}

---

##### `RegionId`<sup>Optional</sup> <a name="RegionId" id="@cdktf/provider-neon.project.ProjectConfig.property.regionId"></a>

```csharp
public string RegionId { get; set; }
```

- *Type:* string

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#region_id Project#region_id}

---

##### `StorePassword`<sup>Optional</sup> <a name="StorePassword" id="@cdktf/provider-neon.project.ProjectConfig.property.storePassword"></a>

```csharp
public object StorePassword { get; set; }
```

- *Type:* object

Whether or not passwords are stored for roles in the Neon project.

Storing passwords facilitates access to Neon features that require authorization.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#store_password Project#store_password}

---

### ProjectDefaultEndpointSettings <a name="ProjectDefaultEndpointSettings" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new ProjectDefaultEndpointSettings {
    double AutoscalingLimitMaxCu = null,
    double AutoscalingLimitMinCu = null,
    double SuspendTimeoutSeconds = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu">AutoscalingLimitMaxCu</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu">AutoscalingLimitMinCu</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds">SuspendTimeoutSeconds</a></code> | <code>double</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |

---

##### `AutoscalingLimitMaxCu`<sup>Optional</sup> <a name="AutoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu"></a>

```csharp
public double AutoscalingLimitMaxCu { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}.

---

##### `AutoscalingLimitMinCu`<sup>Optional</sup> <a name="AutoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu"></a>

```csharp
public double AutoscalingLimitMinCu { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}.

---

##### `SuspendTimeoutSeconds`<sup>Optional</sup> <a name="SuspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds"></a>

```csharp
public double SuspendTimeoutSeconds { get; set; }
```

- *Type:* double

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#suspend_timeout_seconds Project#suspend_timeout_seconds}

---

### ProjectQuota <a name="ProjectQuota" id="@cdktf/provider-neon.project.ProjectQuota"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectQuota.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new ProjectQuota {
    double ActiveTimeSeconds = null,
    double ComputeTimeSeconds = null,
    double DataTransferBytes = null,
    double LogicalSizeBytes = null,
    double WrittenDataBytes = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds">ActiveTimeSeconds</a></code> | <code>double</code> | The total amount of wall-clock time allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds">ComputeTimeSeconds</a></code> | <code>double</code> | The total amount of CPU seconds allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes">DataTransferBytes</a></code> | <code>double</code> | Total amount of data transferred from all of a project's branches using the proxy. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes">LogicalSizeBytes</a></code> | <code>double</code> | Limit on the logical size of every project's branch. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes">WrittenDataBytes</a></code> | <code>double</code> | Total amount of data written to all of a project's branches. |

---

##### `ActiveTimeSeconds`<sup>Optional</sup> <a name="ActiveTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds"></a>

```csharp
public double ActiveTimeSeconds { get; set; }
```

- *Type:* double

The total amount of wall-clock time allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#active_time_seconds Project#active_time_seconds}

---

##### `ComputeTimeSeconds`<sup>Optional</sup> <a name="ComputeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds"></a>

```csharp
public double ComputeTimeSeconds { get; set; }
```

- *Type:* double

The total amount of CPU seconds allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_time_seconds Project#compute_time_seconds}

---

##### `DataTransferBytes`<sup>Optional</sup> <a name="DataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes"></a>

```csharp
public double DataTransferBytes { get; set; }
```

- *Type:* double

Total amount of data transferred from all of a project's branches using the proxy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#data_transfer_bytes Project#data_transfer_bytes}

---

##### `LogicalSizeBytes`<sup>Optional</sup> <a name="LogicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes"></a>

```csharp
public double LogicalSizeBytes { get; set; }
```

- *Type:* double

Limit on the logical size of every project's branch.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#logical_size_bytes Project#logical_size_bytes}

---

##### `WrittenDataBytes`<sup>Optional</sup> <a name="WrittenDataBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes"></a>

```csharp
public double WrittenDataBytes { get; set; }
```

- *Type:* double

Total amount of data written to all of a project's branches.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#written_data_bytes Project#written_data_bytes}

---

## Classes <a name="Classes" id="Classes"></a>

### ProjectBranchOutputReference <a name="ProjectBranchOutputReference" id="@cdktf/provider-neon.project.ProjectBranchOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new ProjectBranchOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resetDatabaseName">ResetDatabaseName</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resetName">ResetName</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resetRoleName">ResetRoleName</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetDatabaseName` <a name="ResetDatabaseName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetDatabaseName"></a>

```csharp
private void ResetDatabaseName()
```

##### `ResetName` <a name="ResetName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetName"></a>

```csharp
private void ResetName()
```

##### `ResetRoleName` <a name="ResetRoleName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetRoleName"></a>

```csharp
private void ResetRoleName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput">DatabaseNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput">RoleNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName">DatabaseName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName">RoleName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `DatabaseNameInput`<sup>Optional</sup> <a name="DatabaseNameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput"></a>

```csharp
public string DatabaseNameInput { get; }
```

- *Type:* string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `RoleNameInput`<sup>Optional</sup> <a name="RoleNameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput"></a>

```csharp
public string RoleNameInput { get; }
```

- *Type:* string

---

##### `DatabaseName`<sup>Required</sup> <a name="DatabaseName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName"></a>

```csharp
public string DatabaseName { get; }
```

- *Type:* string

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `RoleName`<sup>Required</sup> <a name="RoleName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName"></a>

```csharp
public string RoleName { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue"></a>

```csharp
public ProjectBranch InternalValue { get; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---


### ProjectDefaultEndpointSettingsOutputReference <a name="ProjectDefaultEndpointSettingsOutputReference" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new ProjectDefaultEndpointSettingsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMaxCu">ResetAutoscalingLimitMaxCu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMinCu">ResetAutoscalingLimitMinCu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetSuspendTimeoutSeconds">ResetSuspendTimeoutSeconds</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetAutoscalingLimitMaxCu` <a name="ResetAutoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMaxCu"></a>

```csharp
private void ResetAutoscalingLimitMaxCu()
```

##### `ResetAutoscalingLimitMinCu` <a name="ResetAutoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMinCu"></a>

```csharp
private void ResetAutoscalingLimitMinCu()
```

##### `ResetSuspendTimeoutSeconds` <a name="ResetSuspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetSuspendTimeoutSeconds"></a>

```csharp
private void ResetSuspendTimeoutSeconds()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput">AutoscalingLimitMaxCuInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput">AutoscalingLimitMinCuInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput">SuspendTimeoutSecondsInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu">AutoscalingLimitMaxCu</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu">AutoscalingLimitMinCu</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds">SuspendTimeoutSeconds</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `AutoscalingLimitMaxCuInput`<sup>Optional</sup> <a name="AutoscalingLimitMaxCuInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput"></a>

```csharp
public double AutoscalingLimitMaxCuInput { get; }
```

- *Type:* double

---

##### `AutoscalingLimitMinCuInput`<sup>Optional</sup> <a name="AutoscalingLimitMinCuInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput"></a>

```csharp
public double AutoscalingLimitMinCuInput { get; }
```

- *Type:* double

---

##### `SuspendTimeoutSecondsInput`<sup>Optional</sup> <a name="SuspendTimeoutSecondsInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput"></a>

```csharp
public double SuspendTimeoutSecondsInput { get; }
```

- *Type:* double

---

##### `AutoscalingLimitMaxCu`<sup>Required</sup> <a name="AutoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu"></a>

```csharp
public double AutoscalingLimitMaxCu { get; }
```

- *Type:* double

---

##### `AutoscalingLimitMinCu`<sup>Required</sup> <a name="AutoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu"></a>

```csharp
public double AutoscalingLimitMinCu { get; }
```

- *Type:* double

---

##### `SuspendTimeoutSeconds`<sup>Required</sup> <a name="SuspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds"></a>

```csharp
public double SuspendTimeoutSeconds { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue"></a>

```csharp
public ProjectDefaultEndpointSettings InternalValue { get; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---


### ProjectQuotaOutputReference <a name="ProjectQuotaOutputReference" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Neon;

new ProjectQuotaOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetActiveTimeSeconds">ResetActiveTimeSeconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetComputeTimeSeconds">ResetComputeTimeSeconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetDataTransferBytes">ResetDataTransferBytes</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetLogicalSizeBytes">ResetLogicalSizeBytes</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetWrittenDataBytes">ResetWrittenDataBytes</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetActiveTimeSeconds` <a name="ResetActiveTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetActiveTimeSeconds"></a>

```csharp
private void ResetActiveTimeSeconds()
```

##### `ResetComputeTimeSeconds` <a name="ResetComputeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetComputeTimeSeconds"></a>

```csharp
private void ResetComputeTimeSeconds()
```

##### `ResetDataTransferBytes` <a name="ResetDataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetDataTransferBytes"></a>

```csharp
private void ResetDataTransferBytes()
```

##### `ResetLogicalSizeBytes` <a name="ResetLogicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetLogicalSizeBytes"></a>

```csharp
private void ResetLogicalSizeBytes()
```

##### `ResetWrittenDataBytes` <a name="ResetWrittenDataBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetWrittenDataBytes"></a>

```csharp
private void ResetWrittenDataBytes()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput">ActiveTimeSecondsInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput">ComputeTimeSecondsInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput">DataTransferBytesInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput">LogicalSizeBytesInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput">WrittenDataBytesInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds">ActiveTimeSeconds</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds">ComputeTimeSeconds</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes">DataTransferBytes</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes">LogicalSizeBytes</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes">WrittenDataBytes</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `ActiveTimeSecondsInput`<sup>Optional</sup> <a name="ActiveTimeSecondsInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput"></a>

```csharp
public double ActiveTimeSecondsInput { get; }
```

- *Type:* double

---

##### `ComputeTimeSecondsInput`<sup>Optional</sup> <a name="ComputeTimeSecondsInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput"></a>

```csharp
public double ComputeTimeSecondsInput { get; }
```

- *Type:* double

---

##### `DataTransferBytesInput`<sup>Optional</sup> <a name="DataTransferBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput"></a>

```csharp
public double DataTransferBytesInput { get; }
```

- *Type:* double

---

##### `LogicalSizeBytesInput`<sup>Optional</sup> <a name="LogicalSizeBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput"></a>

```csharp
public double LogicalSizeBytesInput { get; }
```

- *Type:* double

---

##### `WrittenDataBytesInput`<sup>Optional</sup> <a name="WrittenDataBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput"></a>

```csharp
public double WrittenDataBytesInput { get; }
```

- *Type:* double

---

##### `ActiveTimeSeconds`<sup>Required</sup> <a name="ActiveTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds"></a>

```csharp
public double ActiveTimeSeconds { get; }
```

- *Type:* double

---

##### `ComputeTimeSeconds`<sup>Required</sup> <a name="ComputeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds"></a>

```csharp
public double ComputeTimeSeconds { get; }
```

- *Type:* double

---

##### `DataTransferBytes`<sup>Required</sup> <a name="DataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes"></a>

```csharp
public double DataTransferBytes { get; }
```

- *Type:* double

---

##### `LogicalSizeBytes`<sup>Required</sup> <a name="LogicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes"></a>

```csharp
public double LogicalSizeBytes { get; }
```

- *Type:* double

---

##### `WrittenDataBytes`<sup>Required</sup> <a name="WrittenDataBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes"></a>

```csharp
public double WrittenDataBytes { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue"></a>

```csharp
public ProjectQuota InternalValue { get; }
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---



