# `neon_project`

Refer to the Terraform Registory for docs: [`neon_project`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project).

# `project` Submodule <a name="`project` Submodule" id="@cdktf/provider-neon.project"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Project <a name="Project" id="@cdktf/provider-neon.project.Project"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project neon_project}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.Project.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

project.NewProject(scope Construct, id *string, config ProjectConfig) Project
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectConfig">ProjectConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.project.Project.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Optional</sup> <a name="config" id="@cdktf/provider-neon.project.Project.Initializer.parameter.config"></a>

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

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="@cdktf/provider-neon.project.Project.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-neon.project.Project.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktf/provider-neon.project.Project.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-neon.project.Project.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktf/provider-neon.project.Project.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="@cdktf/provider-neon.project.Project.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktf/provider-neon.project.Project.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktf/provider-neon.project.Project.addMoveTarget"></a>

```go
func AddMoveTarget(moveTarget *string)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.project.Project.addMoveTarget.parameter.moveTarget"></a>

- *Type:* *string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.project.Project.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.project.Project.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `ImportFrom` <a name="ImportFrom" id="@cdktf/provider-neon.project.Project.importFrom"></a>

```go
func ImportFrom(id *string, provider TerraformProvider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.importFrom.parameter.id"></a>

- *Type:* *string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.importFrom.parameter.provider"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `MoveTo` <a name="MoveTo" id="@cdktf/provider-neon.project.Project.moveTo"></a>

```go
func MoveTo(moveTarget *string, index interface{})
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.project.Project.moveTo.parameter.moveTarget"></a>

- *Type:* *string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-neon.project.Project.moveTo.parameter.index"></a>

- *Type:* interface{}

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `PutBranch` <a name="PutBranch" id="@cdktf/provider-neon.project.Project.putBranch"></a>

```go
func PutBranch(value ProjectBranch)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.putBranch.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---

##### `PutDefaultEndpointSettings` <a name="PutDefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings"></a>

```go
func PutDefaultEndpointSettings(value ProjectDefaultEndpointSettings)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---

##### `PutQuota` <a name="PutQuota" id="@cdktf/provider-neon.project.Project.putQuota"></a>

```go
func PutQuota(value ProjectQuota)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.putQuota.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---

##### `ResetBranch` <a name="ResetBranch" id="@cdktf/provider-neon.project.Project.resetBranch"></a>

```go
func ResetBranch()
```

##### `ResetComputeProvisioner` <a name="ResetComputeProvisioner" id="@cdktf/provider-neon.project.Project.resetComputeProvisioner"></a>

```go
func ResetComputeProvisioner()
```

##### `ResetDefaultEndpointSettings` <a name="ResetDefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.resetDefaultEndpointSettings"></a>

```go
func ResetDefaultEndpointSettings()
```

##### `ResetHistoryRetentionSeconds` <a name="ResetHistoryRetentionSeconds" id="@cdktf/provider-neon.project.Project.resetHistoryRetentionSeconds"></a>

```go
func ResetHistoryRetentionSeconds()
```

##### `ResetName` <a name="ResetName" id="@cdktf/provider-neon.project.Project.resetName"></a>

```go
func ResetName()
```

##### `ResetPgVersion` <a name="ResetPgVersion" id="@cdktf/provider-neon.project.Project.resetPgVersion"></a>

```go
func ResetPgVersion()
```

##### `ResetQuota` <a name="ResetQuota" id="@cdktf/provider-neon.project.Project.resetQuota"></a>

```go
func ResetQuota()
```

##### `ResetRegionId` <a name="ResetRegionId" id="@cdktf/provider-neon.project.Project.resetRegionId"></a>

```go
func ResetRegionId()
```

##### `ResetStorePassword` <a name="ResetStorePassword" id="@cdktf/provider-neon.project.Project.resetStorePassword"></a>

```go
func ResetStorePassword()
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

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

project.Project_IsConstruct(x interface{}) *bool
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.project.Project.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktf/provider-neon.project.Project.isTerraformElement"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

project.Project_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.project.Project.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktf/provider-neon.project.Project.isTerraformResource"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

project.Project_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.project.Project.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktf/provider-neon.project.Project.generateConfigForImport"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

project.Project_GenerateConfigForImport(scope Construct, importToId *string, importFromId *string, provider TerraformProvider) ImportableResource
```

Generates CDKTF code for importing a Project resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importToId"></a>

- *Type:* *string

The construct id used in the generated config for the Project to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importFromId"></a>

- *Type:* *string

The id of the existing Project that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.provider"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

? Optional instance of the provider where the Project to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-neon.project.Project.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branch">Branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connectionUri">ConnectionUri</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseHost">DatabaseHost</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseName">DatabaseName</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databasePassword">DatabasePassword</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseUser">DatabaseUser</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultBranchId">DefaultBranchId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettings">DefaultEndpointSettings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quota">Quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branchInput">BranchInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisionerInput">ComputeProvisionerInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput">DefaultEndpointSettingsInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput">HistoryRetentionSecondsInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersionInput">PgVersionInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quotaInput">QuotaInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionIdInput">RegionIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePasswordInput">StorePasswordInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisioner">ComputeProvisioner</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSeconds">HistoryRetentionSeconds</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersion">PgVersion</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionId">RegionId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePassword">StorePassword</a></code> | <code>interface{}</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktf/provider-neon.project.Project.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktf/provider-neon.project.Project.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.project.Project.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktf/provider-neon.project.Project.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktf/provider-neon.project.Project.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktf/provider-neon.project.Project.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-neon.project.Project.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-neon.project.Project.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-neon.project.Project.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-neon.project.Project.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-neon.project.Project.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.project.Project.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-neon.project.Project.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Branch`<sup>Required</sup> <a name="Branch" id="@cdktf/provider-neon.project.Project.property.branch"></a>

```go
func Branch() ProjectBranchOutputReference
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a>

---

##### `ConnectionUri`<sup>Required</sup> <a name="ConnectionUri" id="@cdktf/provider-neon.project.Project.property.connectionUri"></a>

```go
func ConnectionUri() *string
```

- *Type:* *string

---

##### `DatabaseHost`<sup>Required</sup> <a name="DatabaseHost" id="@cdktf/provider-neon.project.Project.property.databaseHost"></a>

```go
func DatabaseHost() *string
```

- *Type:* *string

---

##### `DatabaseName`<sup>Required</sup> <a name="DatabaseName" id="@cdktf/provider-neon.project.Project.property.databaseName"></a>

```go
func DatabaseName() *string
```

- *Type:* *string

---

##### `DatabasePassword`<sup>Required</sup> <a name="DatabasePassword" id="@cdktf/provider-neon.project.Project.property.databasePassword"></a>

```go
func DatabasePassword() *string
```

- *Type:* *string

---

##### `DatabaseUser`<sup>Required</sup> <a name="DatabaseUser" id="@cdktf/provider-neon.project.Project.property.databaseUser"></a>

```go
func DatabaseUser() *string
```

- *Type:* *string

---

##### `DefaultBranchId`<sup>Required</sup> <a name="DefaultBranchId" id="@cdktf/provider-neon.project.Project.property.defaultBranchId"></a>

```go
func DefaultBranchId() *string
```

- *Type:* *string

---

##### `DefaultEndpointSettings`<sup>Required</sup> <a name="DefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettings"></a>

```go
func DefaultEndpointSettings() ProjectDefaultEndpointSettingsOutputReference
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a>

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.project.Project.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Quota`<sup>Required</sup> <a name="Quota" id="@cdktf/provider-neon.project.Project.property.quota"></a>

```go
func Quota() ProjectQuotaOutputReference
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a>

---

##### `BranchInput`<sup>Optional</sup> <a name="BranchInput" id="@cdktf/provider-neon.project.Project.property.branchInput"></a>

```go
func BranchInput() ProjectBranch
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---

##### `ComputeProvisionerInput`<sup>Optional</sup> <a name="ComputeProvisionerInput" id="@cdktf/provider-neon.project.Project.property.computeProvisionerInput"></a>

```go
func ComputeProvisionerInput() *string
```

- *Type:* *string

---

##### `DefaultEndpointSettingsInput`<sup>Optional</sup> <a name="DefaultEndpointSettingsInput" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput"></a>

```go
func DefaultEndpointSettingsInput() ProjectDefaultEndpointSettings
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---

##### `HistoryRetentionSecondsInput`<sup>Optional</sup> <a name="HistoryRetentionSecondsInput" id="@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput"></a>

```go
func HistoryRetentionSecondsInput() *f64
```

- *Type:* *f64

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktf/provider-neon.project.Project.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `PgVersionInput`<sup>Optional</sup> <a name="PgVersionInput" id="@cdktf/provider-neon.project.Project.property.pgVersionInput"></a>

```go
func PgVersionInput() *f64
```

- *Type:* *f64

---

##### `QuotaInput`<sup>Optional</sup> <a name="QuotaInput" id="@cdktf/provider-neon.project.Project.property.quotaInput"></a>

```go
func QuotaInput() ProjectQuota
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---

##### `RegionIdInput`<sup>Optional</sup> <a name="RegionIdInput" id="@cdktf/provider-neon.project.Project.property.regionIdInput"></a>

```go
func RegionIdInput() *string
```

- *Type:* *string

---

##### `StorePasswordInput`<sup>Optional</sup> <a name="StorePasswordInput" id="@cdktf/provider-neon.project.Project.property.storePasswordInput"></a>

```go
func StorePasswordInput() interface{}
```

- *Type:* interface{}

---

##### `ComputeProvisioner`<sup>Required</sup> <a name="ComputeProvisioner" id="@cdktf/provider-neon.project.Project.property.computeProvisioner"></a>

```go
func ComputeProvisioner() *string
```

- *Type:* *string

---

##### `HistoryRetentionSeconds`<sup>Required</sup> <a name="HistoryRetentionSeconds" id="@cdktf/provider-neon.project.Project.property.historyRetentionSeconds"></a>

```go
func HistoryRetentionSeconds() *f64
```

- *Type:* *f64

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktf/provider-neon.project.Project.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `PgVersion`<sup>Required</sup> <a name="PgVersion" id="@cdktf/provider-neon.project.Project.property.pgVersion"></a>

```go
func PgVersion() *f64
```

- *Type:* *f64

---

##### `RegionId`<sup>Required</sup> <a name="RegionId" id="@cdktf/provider-neon.project.Project.property.regionId"></a>

```go
func RegionId() *string
```

- *Type:* *string

---

##### `StorePassword`<sup>Required</sup> <a name="StorePassword" id="@cdktf/provider-neon.project.Project.property.storePassword"></a>

```go
func StorePassword() interface{}
```

- *Type:* interface{}

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktf/provider-neon.project.Project.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### ProjectBranch <a name="ProjectBranch" id="@cdktf/provider-neon.project.ProjectBranch"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectBranch.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

&project.ProjectBranch {
	DatabaseName: *string,
	Name: *string,
	RoleName: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.databaseName">DatabaseName</a></code> | <code>*string</code> | The database name. If not specified, the default database name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.name">Name</a></code> | <code>*string</code> | The branch name. If not specified, the default branch name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.roleName">RoleName</a></code> | <code>*string</code> | The role name. If not specified, the default role name will be used. |

---

##### `DatabaseName`<sup>Optional</sup> <a name="DatabaseName" id="@cdktf/provider-neon.project.ProjectBranch.property.databaseName"></a>

```go
DatabaseName *string
```

- *Type:* *string

The database name. If not specified, the default database name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#database_name Project#database_name}

---

##### `Name`<sup>Optional</sup> <a name="Name" id="@cdktf/provider-neon.project.ProjectBranch.property.name"></a>

```go
Name *string
```

- *Type:* *string

The branch name. If not specified, the default branch name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `RoleName`<sup>Optional</sup> <a name="RoleName" id="@cdktf/provider-neon.project.ProjectBranch.property.roleName"></a>

```go
RoleName *string
```

- *Type:* *string

The role name. If not specified, the default role name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#role_name Project#role_name}

---

### ProjectConfig <a name="ProjectConfig" id="@cdktf/provider-neon.project.ProjectConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectConfig.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

&project.ProjectConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	Branch: github.com/cdktf/cdktf-provider-neon-go/neon.project.ProjectBranch,
	ComputeProvisioner: *string,
	DefaultEndpointSettings: github.com/cdktf/cdktf-provider-neon-go/neon.project.ProjectDefaultEndpointSettings,
	HistoryRetentionSeconds: *f64,
	Name: *string,
	PgVersion: *f64,
	Quota: github.com/cdktf/cdktf-provider-neon-go/neon.project.ProjectQuota,
	RegionId: *string,
	StorePassword: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.branch">Branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | branch block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner">ComputeProvisioner</a></code> | <code>*string</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings">DefaultEndpointSettings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | default_endpoint_settings block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds">HistoryRetentionSeconds</a></code> | <code>*f64</code> | The number of seconds to retain the point-in-time restore (PITR) backup history for this project. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.name">Name</a></code> | <code>*string</code> | Project name. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.pgVersion">PgVersion</a></code> | <code>*f64</code> | Postgres version. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.quota">Quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | quota block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.regionId">RegionId</a></code> | <code>*string</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.storePassword">StorePassword</a></code> | <code>interface{}</code> | Whether or not passwords are stored for roles in the Neon project. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktf/provider-neon.project.ProjectConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktf/provider-neon.project.ProjectConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktf/provider-neon.project.ProjectConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktf/provider-neon.project.ProjectConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktf/provider-neon.project.ProjectConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktf/provider-neon.project.ProjectConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktf/provider-neon.project.ProjectConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Branch`<sup>Optional</sup> <a name="Branch" id="@cdktf/provider-neon.project.ProjectConfig.property.branch"></a>

```go
Branch ProjectBranch
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

branch block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#branch Project#branch}

---

##### `ComputeProvisioner`<sup>Optional</sup> <a name="ComputeProvisioner" id="@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner"></a>

```go
ComputeProvisioner *string
```

- *Type:* *string

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_provisioner Project#compute_provisioner}

---

##### `DefaultEndpointSettings`<sup>Optional</sup> <a name="DefaultEndpointSettings" id="@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings"></a>

```go
DefaultEndpointSettings ProjectDefaultEndpointSettings
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

default_endpoint_settings block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#default_endpoint_settings Project#default_endpoint_settings}

---

##### `HistoryRetentionSeconds`<sup>Optional</sup> <a name="HistoryRetentionSeconds" id="@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds"></a>

```go
HistoryRetentionSeconds *f64
```

- *Type:* *f64

The number of seconds to retain the point-in-time restore (PITR) backup history for this project.

Default: 7 days, see https://neon.tech/docs/reference/glossary#point-in-time-restore.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#history_retention_seconds Project#history_retention_seconds}

---

##### `Name`<sup>Optional</sup> <a name="Name" id="@cdktf/provider-neon.project.ProjectConfig.property.name"></a>

```go
Name *string
```

- *Type:* *string

Project name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `PgVersion`<sup>Optional</sup> <a name="PgVersion" id="@cdktf/provider-neon.project.ProjectConfig.property.pgVersion"></a>

```go
PgVersion *f64
```

- *Type:* *f64

Postgres version.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#pg_version Project#pg_version}

---

##### `Quota`<sup>Optional</sup> <a name="Quota" id="@cdktf/provider-neon.project.ProjectConfig.property.quota"></a>

```go
Quota ProjectQuota
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

quota block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#quota Project#quota}

---

##### `RegionId`<sup>Optional</sup> <a name="RegionId" id="@cdktf/provider-neon.project.ProjectConfig.property.regionId"></a>

```go
RegionId *string
```

- *Type:* *string

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#region_id Project#region_id}

---

##### `StorePassword`<sup>Optional</sup> <a name="StorePassword" id="@cdktf/provider-neon.project.ProjectConfig.property.storePassword"></a>

```go
StorePassword interface{}
```

- *Type:* interface{}

Whether or not passwords are stored for roles in the Neon project.

Storing passwords facilitates access to Neon features that require authorization.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#store_password Project#store_password}

---

### ProjectDefaultEndpointSettings <a name="ProjectDefaultEndpointSettings" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

&project.ProjectDefaultEndpointSettings {
	AutoscalingLimitMaxCu: *f64,
	AutoscalingLimitMinCu: *f64,
	SuspendTimeoutSeconds: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu">AutoscalingLimitMaxCu</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu">AutoscalingLimitMinCu</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds">SuspendTimeoutSeconds</a></code> | <code>*f64</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |

---

##### `AutoscalingLimitMaxCu`<sup>Optional</sup> <a name="AutoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu"></a>

```go
AutoscalingLimitMaxCu *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}.

---

##### `AutoscalingLimitMinCu`<sup>Optional</sup> <a name="AutoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu"></a>

```go
AutoscalingLimitMinCu *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}.

---

##### `SuspendTimeoutSeconds`<sup>Optional</sup> <a name="SuspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds"></a>

```go
SuspendTimeoutSeconds *f64
```

- *Type:* *f64

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#suspend_timeout_seconds Project#suspend_timeout_seconds}

---

### ProjectQuota <a name="ProjectQuota" id="@cdktf/provider-neon.project.ProjectQuota"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectQuota.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

&project.ProjectQuota {
	ActiveTimeSeconds: *f64,
	ComputeTimeSeconds: *f64,
	DataTransferBytes: *f64,
	LogicalSizeBytes: *f64,
	WrittenDataBytes: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds">ActiveTimeSeconds</a></code> | <code>*f64</code> | The total amount of wall-clock time allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds">ComputeTimeSeconds</a></code> | <code>*f64</code> | The total amount of CPU seconds allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes">DataTransferBytes</a></code> | <code>*f64</code> | Total amount of data transferred from all of a project's branches using the proxy. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes">LogicalSizeBytes</a></code> | <code>*f64</code> | Limit on the logical size of every project's branch. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes">WrittenDataBytes</a></code> | <code>*f64</code> | Total amount of data written to all of a project's branches. |

---

##### `ActiveTimeSeconds`<sup>Optional</sup> <a name="ActiveTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds"></a>

```go
ActiveTimeSeconds *f64
```

- *Type:* *f64

The total amount of wall-clock time allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#active_time_seconds Project#active_time_seconds}

---

##### `ComputeTimeSeconds`<sup>Optional</sup> <a name="ComputeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds"></a>

```go
ComputeTimeSeconds *f64
```

- *Type:* *f64

The total amount of CPU seconds allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_time_seconds Project#compute_time_seconds}

---

##### `DataTransferBytes`<sup>Optional</sup> <a name="DataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes"></a>

```go
DataTransferBytes *f64
```

- *Type:* *f64

Total amount of data transferred from all of a project's branches using the proxy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#data_transfer_bytes Project#data_transfer_bytes}

---

##### `LogicalSizeBytes`<sup>Optional</sup> <a name="LogicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes"></a>

```go
LogicalSizeBytes *f64
```

- *Type:* *f64

Limit on the logical size of every project's branch.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#logical_size_bytes Project#logical_size_bytes}

---

##### `WrittenDataBytes`<sup>Optional</sup> <a name="WrittenDataBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes"></a>

```go
WrittenDataBytes *f64
```

- *Type:* *f64

Total amount of data written to all of a project's branches.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#written_data_bytes Project#written_data_bytes}

---

## Classes <a name="Classes" id="Classes"></a>

### ProjectBranchOutputReference <a name="ProjectBranchOutputReference" id="@cdktf/provider-neon.project.ProjectBranchOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

project.NewProjectBranchOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) ProjectBranchOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetDatabaseName` <a name="ResetDatabaseName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetDatabaseName"></a>

```go
func ResetDatabaseName()
```

##### `ResetName` <a name="ResetName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetName"></a>

```go
func ResetName()
```

##### `ResetRoleName` <a name="ResetRoleName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetRoleName"></a>

```go
func ResetRoleName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput">DatabaseNameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput">RoleNameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName">DatabaseName</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName">RoleName</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `DatabaseNameInput`<sup>Optional</sup> <a name="DatabaseNameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput"></a>

```go
func DatabaseNameInput() *string
```

- *Type:* *string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `RoleNameInput`<sup>Optional</sup> <a name="RoleNameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput"></a>

```go
func RoleNameInput() *string
```

- *Type:* *string

---

##### `DatabaseName`<sup>Required</sup> <a name="DatabaseName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName"></a>

```go
func DatabaseName() *string
```

- *Type:* *string

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `RoleName`<sup>Required</sup> <a name="RoleName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName"></a>

```go
func RoleName() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue"></a>

```go
func InternalValue() ProjectBranch
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---


### ProjectDefaultEndpointSettingsOutputReference <a name="ProjectDefaultEndpointSettingsOutputReference" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

project.NewProjectDefaultEndpointSettingsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) ProjectDefaultEndpointSettingsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetAutoscalingLimitMaxCu` <a name="ResetAutoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMaxCu"></a>

```go
func ResetAutoscalingLimitMaxCu()
```

##### `ResetAutoscalingLimitMinCu` <a name="ResetAutoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMinCu"></a>

```go
func ResetAutoscalingLimitMinCu()
```

##### `ResetSuspendTimeoutSeconds` <a name="ResetSuspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetSuspendTimeoutSeconds"></a>

```go
func ResetSuspendTimeoutSeconds()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput">AutoscalingLimitMaxCuInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput">AutoscalingLimitMinCuInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput">SuspendTimeoutSecondsInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu">AutoscalingLimitMaxCu</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu">AutoscalingLimitMinCu</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds">SuspendTimeoutSeconds</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `AutoscalingLimitMaxCuInput`<sup>Optional</sup> <a name="AutoscalingLimitMaxCuInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput"></a>

```go
func AutoscalingLimitMaxCuInput() *f64
```

- *Type:* *f64

---

##### `AutoscalingLimitMinCuInput`<sup>Optional</sup> <a name="AutoscalingLimitMinCuInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput"></a>

```go
func AutoscalingLimitMinCuInput() *f64
```

- *Type:* *f64

---

##### `SuspendTimeoutSecondsInput`<sup>Optional</sup> <a name="SuspendTimeoutSecondsInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput"></a>

```go
func SuspendTimeoutSecondsInput() *f64
```

- *Type:* *f64

---

##### `AutoscalingLimitMaxCu`<sup>Required</sup> <a name="AutoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu"></a>

```go
func AutoscalingLimitMaxCu() *f64
```

- *Type:* *f64

---

##### `AutoscalingLimitMinCu`<sup>Required</sup> <a name="AutoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu"></a>

```go
func AutoscalingLimitMinCu() *f64
```

- *Type:* *f64

---

##### `SuspendTimeoutSeconds`<sup>Required</sup> <a name="SuspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds"></a>

```go
func SuspendTimeoutSeconds() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue"></a>

```go
func InternalValue() ProjectDefaultEndpointSettings
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---


### ProjectQuotaOutputReference <a name="ProjectQuotaOutputReference" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer"></a>

```go
import "github.com/cdktf/cdktf-provider-neon-go/neon/project"

project.NewProjectQuotaOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) ProjectQuotaOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetActiveTimeSeconds` <a name="ResetActiveTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetActiveTimeSeconds"></a>

```go
func ResetActiveTimeSeconds()
```

##### `ResetComputeTimeSeconds` <a name="ResetComputeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetComputeTimeSeconds"></a>

```go
func ResetComputeTimeSeconds()
```

##### `ResetDataTransferBytes` <a name="ResetDataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetDataTransferBytes"></a>

```go
func ResetDataTransferBytes()
```

##### `ResetLogicalSizeBytes` <a name="ResetLogicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetLogicalSizeBytes"></a>

```go
func ResetLogicalSizeBytes()
```

##### `ResetWrittenDataBytes` <a name="ResetWrittenDataBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetWrittenDataBytes"></a>

```go
func ResetWrittenDataBytes()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput">ActiveTimeSecondsInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput">ComputeTimeSecondsInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput">DataTransferBytesInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput">LogicalSizeBytesInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput">WrittenDataBytesInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds">ActiveTimeSeconds</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds">ComputeTimeSeconds</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes">DataTransferBytes</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes">LogicalSizeBytes</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes">WrittenDataBytes</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `ActiveTimeSecondsInput`<sup>Optional</sup> <a name="ActiveTimeSecondsInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput"></a>

```go
func ActiveTimeSecondsInput() *f64
```

- *Type:* *f64

---

##### `ComputeTimeSecondsInput`<sup>Optional</sup> <a name="ComputeTimeSecondsInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput"></a>

```go
func ComputeTimeSecondsInput() *f64
```

- *Type:* *f64

---

##### `DataTransferBytesInput`<sup>Optional</sup> <a name="DataTransferBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput"></a>

```go
func DataTransferBytesInput() *f64
```

- *Type:* *f64

---

##### `LogicalSizeBytesInput`<sup>Optional</sup> <a name="LogicalSizeBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput"></a>

```go
func LogicalSizeBytesInput() *f64
```

- *Type:* *f64

---

##### `WrittenDataBytesInput`<sup>Optional</sup> <a name="WrittenDataBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput"></a>

```go
func WrittenDataBytesInput() *f64
```

- *Type:* *f64

---

##### `ActiveTimeSeconds`<sup>Required</sup> <a name="ActiveTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds"></a>

```go
func ActiveTimeSeconds() *f64
```

- *Type:* *f64

---

##### `ComputeTimeSeconds`<sup>Required</sup> <a name="ComputeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds"></a>

```go
func ComputeTimeSeconds() *f64
```

- *Type:* *f64

---

##### `DataTransferBytes`<sup>Required</sup> <a name="DataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes"></a>

```go
func DataTransferBytes() *f64
```

- *Type:* *f64

---

##### `LogicalSizeBytes`<sup>Required</sup> <a name="LogicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes"></a>

```go
func LogicalSizeBytes() *f64
```

- *Type:* *f64

---

##### `WrittenDataBytes`<sup>Required</sup> <a name="WrittenDataBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes"></a>

```go
func WrittenDataBytes() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue"></a>

```go
func InternalValue() ProjectQuota
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---



