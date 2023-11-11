# `neon_project`

Refer to the Terraform Registory for docs: [`neon_project`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project).

# `project` Submodule <a name="`project` Submodule" id="@cdktf/provider-neon.project"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Project <a name="Project" id="@cdktf/provider-neon.project.Project"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project neon_project}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.Project.Initializer"></a>

```typescript
import { project } from '@cdktf/provider-neon'

new project.Project(scope: Construct, id: string, config?: ProjectConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectConfig">ProjectConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.project.Project.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Optional</sup> <a name="config" id="@cdktf/provider-neon.project.Project.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectConfig">ProjectConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-neon.project.Project.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-neon.project.Project.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-neon.project.Project.addMoveTarget">addMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktf/provider-neon.project.Project.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.importFrom">importFrom</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.moveTo">moveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktf/provider-neon.project.Project.putBranch">putBranch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.putDefaultEndpointSettings">putDefaultEndpointSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.putQuota">putQuota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetBranch">resetBranch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetComputeProvisioner">resetComputeProvisioner</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetDefaultEndpointSettings">resetDefaultEndpointSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetHistoryRetentionSeconds">resetHistoryRetentionSeconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetName">resetName</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetPgVersion">resetPgVersion</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetQuota">resetQuota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetRegionId">resetRegionId</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetStorePassword">resetStorePassword</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktf/provider-neon.project.Project.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="@cdktf/provider-neon.project.Project.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-neon.project.Project.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktf/provider-neon.project.Project.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-neon.project.Project.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktf/provider-neon.project.Project.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="@cdktf/provider-neon.project.Project.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="@cdktf/provider-neon.project.Project.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktf/provider-neon.project.Project.addMoveTarget"></a>

```typescript
public addMoveTarget(moveTarget: string): void
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.project.Project.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.project.Project.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.project.Project.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `importFrom` <a name="importFrom" id="@cdktf/provider-neon.project.Project.importFrom"></a>

```typescript
public importFrom(id: string, provider?: TerraformProvider): void
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.importFrom.parameter.id"></a>

- *Type:* string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.importFrom.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `moveTo` <a name="moveTo" id="@cdktf/provider-neon.project.Project.moveTo"></a>

```typescript
public moveTo(moveTarget: string, index?: string | number): void
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.project.Project.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-neon.project.Project.moveTo.parameter.index"></a>

- *Type:* string | number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `putBranch` <a name="putBranch" id="@cdktf/provider-neon.project.Project.putBranch"></a>

```typescript
public putBranch(value: ProjectBranch): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.putBranch.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---

##### `putDefaultEndpointSettings` <a name="putDefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings"></a>

```typescript
public putDefaultEndpointSettings(value: ProjectDefaultEndpointSettings): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---

##### `putQuota` <a name="putQuota" id="@cdktf/provider-neon.project.Project.putQuota"></a>

```typescript
public putQuota(value: ProjectQuota): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.putQuota.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---

##### `resetBranch` <a name="resetBranch" id="@cdktf/provider-neon.project.Project.resetBranch"></a>

```typescript
public resetBranch(): void
```

##### `resetComputeProvisioner` <a name="resetComputeProvisioner" id="@cdktf/provider-neon.project.Project.resetComputeProvisioner"></a>

```typescript
public resetComputeProvisioner(): void
```

##### `resetDefaultEndpointSettings` <a name="resetDefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.resetDefaultEndpointSettings"></a>

```typescript
public resetDefaultEndpointSettings(): void
```

##### `resetHistoryRetentionSeconds` <a name="resetHistoryRetentionSeconds" id="@cdktf/provider-neon.project.Project.resetHistoryRetentionSeconds"></a>

```typescript
public resetHistoryRetentionSeconds(): void
```

##### `resetName` <a name="resetName" id="@cdktf/provider-neon.project.Project.resetName"></a>

```typescript
public resetName(): void
```

##### `resetPgVersion` <a name="resetPgVersion" id="@cdktf/provider-neon.project.Project.resetPgVersion"></a>

```typescript
public resetPgVersion(): void
```

##### `resetQuota` <a name="resetQuota" id="@cdktf/provider-neon.project.Project.resetQuota"></a>

```typescript
public resetQuota(): void
```

##### `resetRegionId` <a name="resetRegionId" id="@cdktf/provider-neon.project.Project.resetRegionId"></a>

```typescript
public resetRegionId(): void
```

##### `resetStorePassword` <a name="resetStorePassword" id="@cdktf/provider-neon.project.Project.resetStorePassword"></a>

```typescript
public resetStorePassword(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.isTerraformResource">isTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTF code for importing a Project resource upon running "cdktf plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktf/provider-neon.project.Project.isConstruct"></a>

```typescript
import { project } from '@cdktf/provider-neon'

project.Project.isConstruct(x: any)
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

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktf/provider-neon.project.Project.isTerraformElement"></a>

```typescript
import { project } from '@cdktf/provider-neon'

project.Project.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.project.Project.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktf/provider-neon.project.Project.isTerraformResource"></a>

```typescript
import { project } from '@cdktf/provider-neon'

project.Project.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.project.Project.isTerraformResource.parameter.x"></a>

- *Type:* any

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktf/provider-neon.project.Project.generateConfigForImport"></a>

```typescript
import { project } from '@cdktf/provider-neon'

project.Project.generateConfigForImport(scope: Construct, importToId: string, importFromId: string, provider?: TerraformProvider)
```

Generates CDKTF code for importing a Project resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Project to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Project that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

? Optional instance of the provider where the Project to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-neon.project.Project.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branch">branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connectionUri">connectionUri</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseHost">databaseHost</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseName">databaseName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databasePassword">databasePassword</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseUser">databaseUser</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultBranchId">defaultBranchId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettings">defaultEndpointSettings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quota">quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branchInput">branchInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisionerInput">computeProvisionerInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput">defaultEndpointSettingsInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput">historyRetentionSecondsInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersionInput">pgVersionInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quotaInput">quotaInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionIdInput">regionIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePasswordInput">storePasswordInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisioner">computeProvisioner</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSeconds">historyRetentionSeconds</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersion">pgVersion</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionId">regionId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePassword">storePassword</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-neon.project.Project.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktf/provider-neon.project.Project.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.Project.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktf/provider-neon.project.Project.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktf/provider-neon.project.Project.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktf/provider-neon.project.Project.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.project.Project.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.project.Project.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.project.Project.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.project.Project.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.project.Project.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.project.Project.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `branch`<sup>Required</sup> <a name="branch" id="@cdktf/provider-neon.project.Project.property.branch"></a>

```typescript
public readonly branch: ProjectBranchOutputReference;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a>

---

##### `connectionUri`<sup>Required</sup> <a name="connectionUri" id="@cdktf/provider-neon.project.Project.property.connectionUri"></a>

```typescript
public readonly connectionUri: string;
```

- *Type:* string

---

##### `databaseHost`<sup>Required</sup> <a name="databaseHost" id="@cdktf/provider-neon.project.Project.property.databaseHost"></a>

```typescript
public readonly databaseHost: string;
```

- *Type:* string

---

##### `databaseName`<sup>Required</sup> <a name="databaseName" id="@cdktf/provider-neon.project.Project.property.databaseName"></a>

```typescript
public readonly databaseName: string;
```

- *Type:* string

---

##### `databasePassword`<sup>Required</sup> <a name="databasePassword" id="@cdktf/provider-neon.project.Project.property.databasePassword"></a>

```typescript
public readonly databasePassword: string;
```

- *Type:* string

---

##### `databaseUser`<sup>Required</sup> <a name="databaseUser" id="@cdktf/provider-neon.project.Project.property.databaseUser"></a>

```typescript
public readonly databaseUser: string;
```

- *Type:* string

---

##### `defaultBranchId`<sup>Required</sup> <a name="defaultBranchId" id="@cdktf/provider-neon.project.Project.property.defaultBranchId"></a>

```typescript
public readonly defaultBranchId: string;
```

- *Type:* string

---

##### `defaultEndpointSettings`<sup>Required</sup> <a name="defaultEndpointSettings" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettings"></a>

```typescript
public readonly defaultEndpointSettings: ProjectDefaultEndpointSettingsOutputReference;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a>

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `quota`<sup>Required</sup> <a name="quota" id="@cdktf/provider-neon.project.Project.property.quota"></a>

```typescript
public readonly quota: ProjectQuotaOutputReference;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a>

---

##### `branchInput`<sup>Optional</sup> <a name="branchInput" id="@cdktf/provider-neon.project.Project.property.branchInput"></a>

```typescript
public readonly branchInput: ProjectBranch;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---

##### `computeProvisionerInput`<sup>Optional</sup> <a name="computeProvisionerInput" id="@cdktf/provider-neon.project.Project.property.computeProvisionerInput"></a>

```typescript
public readonly computeProvisionerInput: string;
```

- *Type:* string

---

##### `defaultEndpointSettingsInput`<sup>Optional</sup> <a name="defaultEndpointSettingsInput" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput"></a>

```typescript
public readonly defaultEndpointSettingsInput: ProjectDefaultEndpointSettings;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---

##### `historyRetentionSecondsInput`<sup>Optional</sup> <a name="historyRetentionSecondsInput" id="@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput"></a>

```typescript
public readonly historyRetentionSecondsInput: number;
```

- *Type:* number

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktf/provider-neon.project.Project.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `pgVersionInput`<sup>Optional</sup> <a name="pgVersionInput" id="@cdktf/provider-neon.project.Project.property.pgVersionInput"></a>

```typescript
public readonly pgVersionInput: number;
```

- *Type:* number

---

##### `quotaInput`<sup>Optional</sup> <a name="quotaInput" id="@cdktf/provider-neon.project.Project.property.quotaInput"></a>

```typescript
public readonly quotaInput: ProjectQuota;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---

##### `regionIdInput`<sup>Optional</sup> <a name="regionIdInput" id="@cdktf/provider-neon.project.Project.property.regionIdInput"></a>

```typescript
public readonly regionIdInput: string;
```

- *Type:* string

---

##### `storePasswordInput`<sup>Optional</sup> <a name="storePasswordInput" id="@cdktf/provider-neon.project.Project.property.storePasswordInput"></a>

```typescript
public readonly storePasswordInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `computeProvisioner`<sup>Required</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.project.Project.property.computeProvisioner"></a>

```typescript
public readonly computeProvisioner: string;
```

- *Type:* string

---

##### `historyRetentionSeconds`<sup>Required</sup> <a name="historyRetentionSeconds" id="@cdktf/provider-neon.project.Project.property.historyRetentionSeconds"></a>

```typescript
public readonly historyRetentionSeconds: number;
```

- *Type:* number

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktf/provider-neon.project.Project.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `pgVersion`<sup>Required</sup> <a name="pgVersion" id="@cdktf/provider-neon.project.Project.property.pgVersion"></a>

```typescript
public readonly pgVersion: number;
```

- *Type:* number

---

##### `regionId`<sup>Required</sup> <a name="regionId" id="@cdktf/provider-neon.project.Project.property.regionId"></a>

```typescript
public readonly regionId: string;
```

- *Type:* string

---

##### `storePassword`<sup>Required</sup> <a name="storePassword" id="@cdktf/provider-neon.project.Project.property.storePassword"></a>

```typescript
public readonly storePassword: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-neon.project.Project.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ProjectBranch <a name="ProjectBranch" id="@cdktf/provider-neon.project.ProjectBranch"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectBranch.Initializer"></a>

```typescript
import { project } from '@cdktf/provider-neon'

const projectBranch: project.ProjectBranch = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.databaseName">databaseName</a></code> | <code>string</code> | The database name. If not specified, the default database name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.name">name</a></code> | <code>string</code> | The branch name. If not specified, the default branch name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.roleName">roleName</a></code> | <code>string</code> | The role name. If not specified, the default role name will be used. |

---

##### `databaseName`<sup>Optional</sup> <a name="databaseName" id="@cdktf/provider-neon.project.ProjectBranch.property.databaseName"></a>

```typescript
public readonly databaseName: string;
```

- *Type:* string

The database name. If not specified, the default database name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#database_name Project#database_name}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktf/provider-neon.project.ProjectBranch.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

The branch name. If not specified, the default branch name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `roleName`<sup>Optional</sup> <a name="roleName" id="@cdktf/provider-neon.project.ProjectBranch.property.roleName"></a>

```typescript
public readonly roleName: string;
```

- *Type:* string

The role name. If not specified, the default role name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#role_name Project#role_name}

---

### ProjectConfig <a name="ProjectConfig" id="@cdktf/provider-neon.project.ProjectConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectConfig.Initializer"></a>

```typescript
import { project } from '@cdktf/provider-neon'

const projectConfig: project.ProjectConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.branch">branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | branch block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner">computeProvisioner</a></code> | <code>string</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings">defaultEndpointSettings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | default_endpoint_settings block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds">historyRetentionSeconds</a></code> | <code>number</code> | The number of seconds to retain the point-in-time restore (PITR) backup history for this project. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.name">name</a></code> | <code>string</code> | Project name. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.pgVersion">pgVersion</a></code> | <code>number</code> | Postgres version. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.quota">quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | quota block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.regionId">regionId</a></code> | <code>string</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.storePassword">storePassword</a></code> | <code>boolean \| cdktf.IResolvable</code> | Whether or not passwords are stored for roles in the Neon project. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.project.ProjectConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.project.ProjectConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.project.ProjectConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.project.ProjectConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.project.ProjectConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.ProjectConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.project.ProjectConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `branch`<sup>Optional</sup> <a name="branch" id="@cdktf/provider-neon.project.ProjectConfig.property.branch"></a>

```typescript
public readonly branch: ProjectBranch;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

branch block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#branch Project#branch}

---

##### `computeProvisioner`<sup>Optional</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner"></a>

```typescript
public readonly computeProvisioner: string;
```

- *Type:* string

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_provisioner Project#compute_provisioner}

---

##### `defaultEndpointSettings`<sup>Optional</sup> <a name="defaultEndpointSettings" id="@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings"></a>

```typescript
public readonly defaultEndpointSettings: ProjectDefaultEndpointSettings;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

default_endpoint_settings block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#default_endpoint_settings Project#default_endpoint_settings}

---

##### `historyRetentionSeconds`<sup>Optional</sup> <a name="historyRetentionSeconds" id="@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds"></a>

```typescript
public readonly historyRetentionSeconds: number;
```

- *Type:* number

The number of seconds to retain the point-in-time restore (PITR) backup history for this project.

Default: 7 days, see https://neon.tech/docs/reference/glossary#point-in-time-restore.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#history_retention_seconds Project#history_retention_seconds}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktf/provider-neon.project.ProjectConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Project name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `pgVersion`<sup>Optional</sup> <a name="pgVersion" id="@cdktf/provider-neon.project.ProjectConfig.property.pgVersion"></a>

```typescript
public readonly pgVersion: number;
```

- *Type:* number

Postgres version.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#pg_version Project#pg_version}

---

##### `quota`<sup>Optional</sup> <a name="quota" id="@cdktf/provider-neon.project.ProjectConfig.property.quota"></a>

```typescript
public readonly quota: ProjectQuota;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

quota block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#quota Project#quota}

---

##### `regionId`<sup>Optional</sup> <a name="regionId" id="@cdktf/provider-neon.project.ProjectConfig.property.regionId"></a>

```typescript
public readonly regionId: string;
```

- *Type:* string

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#region_id Project#region_id}

---

##### `storePassword`<sup>Optional</sup> <a name="storePassword" id="@cdktf/provider-neon.project.ProjectConfig.property.storePassword"></a>

```typescript
public readonly storePassword: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Whether or not passwords are stored for roles in the Neon project.

Storing passwords facilitates access to Neon features that require authorization.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#store_password Project#store_password}

---

### ProjectDefaultEndpointSettings <a name="ProjectDefaultEndpointSettings" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.Initializer"></a>

```typescript
import { project } from '@cdktf/provider-neon'

const projectDefaultEndpointSettings: project.ProjectDefaultEndpointSettings = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu">autoscalingLimitMaxCu</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu">autoscalingLimitMinCu</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds">suspendTimeoutSeconds</a></code> | <code>number</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |

---

##### `autoscalingLimitMaxCu`<sup>Optional</sup> <a name="autoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu"></a>

```typescript
public readonly autoscalingLimitMaxCu: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}.

---

##### `autoscalingLimitMinCu`<sup>Optional</sup> <a name="autoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu"></a>

```typescript
public readonly autoscalingLimitMinCu: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}.

---

##### `suspendTimeoutSeconds`<sup>Optional</sup> <a name="suspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds"></a>

```typescript
public readonly suspendTimeoutSeconds: number;
```

- *Type:* number

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#suspend_timeout_seconds Project#suspend_timeout_seconds}

---

### ProjectQuota <a name="ProjectQuota" id="@cdktf/provider-neon.project.ProjectQuota"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectQuota.Initializer"></a>

```typescript
import { project } from '@cdktf/provider-neon'

const projectQuota: project.ProjectQuota = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds">activeTimeSeconds</a></code> | <code>number</code> | The total amount of wall-clock time allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds">computeTimeSeconds</a></code> | <code>number</code> | The total amount of CPU seconds allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes">dataTransferBytes</a></code> | <code>number</code> | Total amount of data transferred from all of a project's branches using the proxy. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes">logicalSizeBytes</a></code> | <code>number</code> | Limit on the logical size of every project's branch. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes">writtenDataBytes</a></code> | <code>number</code> | Total amount of data written to all of a project's branches. |

---

##### `activeTimeSeconds`<sup>Optional</sup> <a name="activeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds"></a>

```typescript
public readonly activeTimeSeconds: number;
```

- *Type:* number

The total amount of wall-clock time allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#active_time_seconds Project#active_time_seconds}

---

##### `computeTimeSeconds`<sup>Optional</sup> <a name="computeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds"></a>

```typescript
public readonly computeTimeSeconds: number;
```

- *Type:* number

The total amount of CPU seconds allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_time_seconds Project#compute_time_seconds}

---

##### `dataTransferBytes`<sup>Optional</sup> <a name="dataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes"></a>

```typescript
public readonly dataTransferBytes: number;
```

- *Type:* number

Total amount of data transferred from all of a project's branches using the proxy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#data_transfer_bytes Project#data_transfer_bytes}

---

##### `logicalSizeBytes`<sup>Optional</sup> <a name="logicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes"></a>

```typescript
public readonly logicalSizeBytes: number;
```

- *Type:* number

Limit on the logical size of every project's branch.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#logical_size_bytes Project#logical_size_bytes}

---

##### `writtenDataBytes`<sup>Optional</sup> <a name="writtenDataBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes"></a>

```typescript
public readonly writtenDataBytes: number;
```

- *Type:* number

Total amount of data written to all of a project's branches.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#written_data_bytes Project#written_data_bytes}

---

## Classes <a name="Classes" id="Classes"></a>

### ProjectBranchOutputReference <a name="ProjectBranchOutputReference" id="@cdktf/provider-neon.project.ProjectBranchOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer"></a>

```typescript
import { project } from '@cdktf/provider-neon'

new project.ProjectBranchOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resetDatabaseName">resetDatabaseName</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resetName">resetName</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resetRoleName">resetRoleName</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetDatabaseName` <a name="resetDatabaseName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetDatabaseName"></a>

```typescript
public resetDatabaseName(): void
```

##### `resetName` <a name="resetName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetName"></a>

```typescript
public resetName(): void
```

##### `resetRoleName` <a name="resetRoleName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetRoleName"></a>

```typescript
public resetRoleName(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput">databaseNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput">roleNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName">databaseName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName">roleName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `databaseNameInput`<sup>Optional</sup> <a name="databaseNameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput"></a>

```typescript
public readonly databaseNameInput: string;
```

- *Type:* string

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `roleNameInput`<sup>Optional</sup> <a name="roleNameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput"></a>

```typescript
public readonly roleNameInput: string;
```

- *Type:* string

---

##### `databaseName`<sup>Required</sup> <a name="databaseName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName"></a>

```typescript
public readonly databaseName: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `roleName`<sup>Required</sup> <a name="roleName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName"></a>

```typescript
public readonly roleName: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: ProjectBranch;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---


### ProjectDefaultEndpointSettingsOutputReference <a name="ProjectDefaultEndpointSettingsOutputReference" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer"></a>

```typescript
import { project } from '@cdktf/provider-neon'

new project.ProjectDefaultEndpointSettingsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMaxCu">resetAutoscalingLimitMaxCu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMinCu">resetAutoscalingLimitMinCu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetSuspendTimeoutSeconds">resetSuspendTimeoutSeconds</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetAutoscalingLimitMaxCu` <a name="resetAutoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMaxCu"></a>

```typescript
public resetAutoscalingLimitMaxCu(): void
```

##### `resetAutoscalingLimitMinCu` <a name="resetAutoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMinCu"></a>

```typescript
public resetAutoscalingLimitMinCu(): void
```

##### `resetSuspendTimeoutSeconds` <a name="resetSuspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetSuspendTimeoutSeconds"></a>

```typescript
public resetSuspendTimeoutSeconds(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput">autoscalingLimitMaxCuInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput">autoscalingLimitMinCuInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput">suspendTimeoutSecondsInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu">autoscalingLimitMaxCu</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu">autoscalingLimitMinCu</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds">suspendTimeoutSeconds</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `autoscalingLimitMaxCuInput`<sup>Optional</sup> <a name="autoscalingLimitMaxCuInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput"></a>

```typescript
public readonly autoscalingLimitMaxCuInput: number;
```

- *Type:* number

---

##### `autoscalingLimitMinCuInput`<sup>Optional</sup> <a name="autoscalingLimitMinCuInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput"></a>

```typescript
public readonly autoscalingLimitMinCuInput: number;
```

- *Type:* number

---

##### `suspendTimeoutSecondsInput`<sup>Optional</sup> <a name="suspendTimeoutSecondsInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput"></a>

```typescript
public readonly suspendTimeoutSecondsInput: number;
```

- *Type:* number

---

##### `autoscalingLimitMaxCu`<sup>Required</sup> <a name="autoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu"></a>

```typescript
public readonly autoscalingLimitMaxCu: number;
```

- *Type:* number

---

##### `autoscalingLimitMinCu`<sup>Required</sup> <a name="autoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu"></a>

```typescript
public readonly autoscalingLimitMinCu: number;
```

- *Type:* number

---

##### `suspendTimeoutSeconds`<sup>Required</sup> <a name="suspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds"></a>

```typescript
public readonly suspendTimeoutSeconds: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: ProjectDefaultEndpointSettings;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---


### ProjectQuotaOutputReference <a name="ProjectQuotaOutputReference" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer"></a>

```typescript
import { project } from '@cdktf/provider-neon'

new project.ProjectQuotaOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetActiveTimeSeconds">resetActiveTimeSeconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetComputeTimeSeconds">resetComputeTimeSeconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetDataTransferBytes">resetDataTransferBytes</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetLogicalSizeBytes">resetLogicalSizeBytes</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetWrittenDataBytes">resetWrittenDataBytes</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetActiveTimeSeconds` <a name="resetActiveTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetActiveTimeSeconds"></a>

```typescript
public resetActiveTimeSeconds(): void
```

##### `resetComputeTimeSeconds` <a name="resetComputeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetComputeTimeSeconds"></a>

```typescript
public resetComputeTimeSeconds(): void
```

##### `resetDataTransferBytes` <a name="resetDataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetDataTransferBytes"></a>

```typescript
public resetDataTransferBytes(): void
```

##### `resetLogicalSizeBytes` <a name="resetLogicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetLogicalSizeBytes"></a>

```typescript
public resetLogicalSizeBytes(): void
```

##### `resetWrittenDataBytes` <a name="resetWrittenDataBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetWrittenDataBytes"></a>

```typescript
public resetWrittenDataBytes(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput">activeTimeSecondsInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput">computeTimeSecondsInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput">dataTransferBytesInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput">logicalSizeBytesInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput">writtenDataBytesInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds">activeTimeSeconds</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds">computeTimeSeconds</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes">dataTransferBytes</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes">logicalSizeBytes</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes">writtenDataBytes</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `activeTimeSecondsInput`<sup>Optional</sup> <a name="activeTimeSecondsInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput"></a>

```typescript
public readonly activeTimeSecondsInput: number;
```

- *Type:* number

---

##### `computeTimeSecondsInput`<sup>Optional</sup> <a name="computeTimeSecondsInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput"></a>

```typescript
public readonly computeTimeSecondsInput: number;
```

- *Type:* number

---

##### `dataTransferBytesInput`<sup>Optional</sup> <a name="dataTransferBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput"></a>

```typescript
public readonly dataTransferBytesInput: number;
```

- *Type:* number

---

##### `logicalSizeBytesInput`<sup>Optional</sup> <a name="logicalSizeBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput"></a>

```typescript
public readonly logicalSizeBytesInput: number;
```

- *Type:* number

---

##### `writtenDataBytesInput`<sup>Optional</sup> <a name="writtenDataBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput"></a>

```typescript
public readonly writtenDataBytesInput: number;
```

- *Type:* number

---

##### `activeTimeSeconds`<sup>Required</sup> <a name="activeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds"></a>

```typescript
public readonly activeTimeSeconds: number;
```

- *Type:* number

---

##### `computeTimeSeconds`<sup>Required</sup> <a name="computeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds"></a>

```typescript
public readonly computeTimeSeconds: number;
```

- *Type:* number

---

##### `dataTransferBytes`<sup>Required</sup> <a name="dataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes"></a>

```typescript
public readonly dataTransferBytes: number;
```

- *Type:* number

---

##### `logicalSizeBytes`<sup>Required</sup> <a name="logicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes"></a>

```typescript
public readonly logicalSizeBytes: number;
```

- *Type:* number

---

##### `writtenDataBytes`<sup>Required</sup> <a name="writtenDataBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes"></a>

```typescript
public readonly writtenDataBytes: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: ProjectQuota;
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---



