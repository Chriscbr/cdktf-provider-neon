# `neon_endpoint`

Refer to the Terraform Registory for docs: [`neon_endpoint`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint).

# `endpoint` Submodule <a name="`endpoint` Submodule" id="@cdktf/provider-neon.endpoint"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Endpoint <a name="Endpoint" id="@cdktf/provider-neon.endpoint.Endpoint"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint neon_endpoint}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer"></a>

```typescript
import { endpoint } from '@cdktf/provider-neon'

new endpoint.Endpoint(scope: Construct, id: string, config: EndpointConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig">EndpointConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktf/provider-neon.endpoint.EndpointConfig">EndpointConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget">addMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.importFrom">importFrom</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.moveTo">moveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMaxCu">resetAutoscalingLimitMaxCu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMinCu">resetAutoscalingLimitMinCu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetComputeProvisioner">resetComputeProvisioner</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetDisabled">resetDisabled</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetPgSettings">resetPgSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetPoolerEnabled">resetPoolerEnabled</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetPoolerMode">resetPoolerMode</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetRegionId">resetRegionId</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetSuspendTimeoutSeconds">resetSuspendTimeoutSeconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetType">resetType</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktf/provider-neon.endpoint.Endpoint.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="@cdktf/provider-neon.endpoint.Endpoint.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="@cdktf/provider-neon.endpoint.Endpoint.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget"></a>

```typescript
public addMoveTarget(moveTarget: string): void
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `importFrom` <a name="importFrom" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom"></a>

```typescript
public importFrom(id: string, provider?: TerraformProvider): void
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.id"></a>

- *Type:* string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `moveTo` <a name="moveTo" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo"></a>

```typescript
public moveTo(moveTarget: string, index?: string | number): void
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.index"></a>

- *Type:* string | number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `resetAutoscalingLimitMaxCu` <a name="resetAutoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMaxCu"></a>

```typescript
public resetAutoscalingLimitMaxCu(): void
```

##### `resetAutoscalingLimitMinCu` <a name="resetAutoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMinCu"></a>

```typescript
public resetAutoscalingLimitMinCu(): void
```

##### `resetComputeProvisioner` <a name="resetComputeProvisioner" id="@cdktf/provider-neon.endpoint.Endpoint.resetComputeProvisioner"></a>

```typescript
public resetComputeProvisioner(): void
```

##### `resetDisabled` <a name="resetDisabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetDisabled"></a>

```typescript
public resetDisabled(): void
```

##### `resetPgSettings` <a name="resetPgSettings" id="@cdktf/provider-neon.endpoint.Endpoint.resetPgSettings"></a>

```typescript
public resetPgSettings(): void
```

##### `resetPoolerEnabled` <a name="resetPoolerEnabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerEnabled"></a>

```typescript
public resetPoolerEnabled(): void
```

##### `resetPoolerMode` <a name="resetPoolerMode" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerMode"></a>

```typescript
public resetPoolerMode(): void
```

##### `resetRegionId` <a name="resetRegionId" id="@cdktf/provider-neon.endpoint.Endpoint.resetRegionId"></a>

```typescript
public resetRegionId(): void
```

##### `resetSuspendTimeoutSeconds` <a name="resetSuspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.Endpoint.resetSuspendTimeoutSeconds"></a>

```typescript
public resetSuspendTimeoutSeconds(): void
```

##### `resetType` <a name="resetType" id="@cdktf/provider-neon.endpoint.Endpoint.resetType"></a>

```typescript
public resetType(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource">isTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTF code for importing a Endpoint resource upon running "cdktf plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktf/provider-neon.endpoint.Endpoint.isConstruct"></a>

```typescript
import { endpoint } from '@cdktf/provider-neon'

endpoint.Endpoint.isConstruct(x: any)
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

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement"></a>

```typescript
import { endpoint } from '@cdktf/provider-neon'

endpoint.Endpoint.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource"></a>

```typescript
import { endpoint } from '@cdktf/provider-neon'

endpoint.Endpoint.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource.parameter.x"></a>

- *Type:* any

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport"></a>

```typescript
import { endpoint } from '@cdktf/provider-neon'

endpoint.Endpoint.generateConfigForImport(scope: Construct, importToId: string, importFromId: string, provider?: TerraformProvider)
```

Generates CDKTF code for importing a Endpoint resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Endpoint to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Endpoint that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

? Optional instance of the provider where the Endpoint to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.host">host</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost">proxyHost</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput">autoscalingLimitMaxCuInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput">autoscalingLimitMinCuInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput">branchIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput">computeProvisionerInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput">disabledInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput">pgSettingsInput</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput">poolerEnabledInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput">poolerModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput">projectIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput">regionIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput">suspendTimeoutSecondsInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu">autoscalingLimitMaxCu</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu">autoscalingLimitMinCu</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchId">branchId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner">computeProvisioner</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabled">disabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings">pgSettings</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled">poolerEnabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode">poolerMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectId">projectId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionId">regionId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds">suspendTimeoutSeconds</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.type">type</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-neon.endpoint.Endpoint.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.endpoint.Endpoint.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.endpoint.Endpoint.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.endpoint.Endpoint.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.endpoint.Endpoint.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.endpoint.Endpoint.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `host`<sup>Required</sup> <a name="host" id="@cdktf/provider-neon.endpoint.Endpoint.property.host"></a>

```typescript
public readonly host: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `proxyHost`<sup>Required</sup> <a name="proxyHost" id="@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost"></a>

```typescript
public readonly proxyHost: string;
```

- *Type:* string

---

##### `autoscalingLimitMaxCuInput`<sup>Optional</sup> <a name="autoscalingLimitMaxCuInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput"></a>

```typescript
public readonly autoscalingLimitMaxCuInput: number;
```

- *Type:* number

---

##### `autoscalingLimitMinCuInput`<sup>Optional</sup> <a name="autoscalingLimitMinCuInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput"></a>

```typescript
public readonly autoscalingLimitMinCuInput: number;
```

- *Type:* number

---

##### `branchIdInput`<sup>Optional</sup> <a name="branchIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput"></a>

```typescript
public readonly branchIdInput: string;
```

- *Type:* string

---

##### `computeProvisionerInput`<sup>Optional</sup> <a name="computeProvisionerInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput"></a>

```typescript
public readonly computeProvisionerInput: string;
```

- *Type:* string

---

##### `disabledInput`<sup>Optional</sup> <a name="disabledInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput"></a>

```typescript
public readonly disabledInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `pgSettingsInput`<sup>Optional</sup> <a name="pgSettingsInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput"></a>

```typescript
public readonly pgSettingsInput: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `poolerEnabledInput`<sup>Optional</sup> <a name="poolerEnabledInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput"></a>

```typescript
public readonly poolerEnabledInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `poolerModeInput`<sup>Optional</sup> <a name="poolerModeInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput"></a>

```typescript
public readonly poolerModeInput: string;
```

- *Type:* string

---

##### `projectIdInput`<sup>Optional</sup> <a name="projectIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput"></a>

```typescript
public readonly projectIdInput: string;
```

- *Type:* string

---

##### `regionIdInput`<sup>Optional</sup> <a name="regionIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput"></a>

```typescript
public readonly regionIdInput: string;
```

- *Type:* string

---

##### `suspendTimeoutSecondsInput`<sup>Optional</sup> <a name="suspendTimeoutSecondsInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput"></a>

```typescript
public readonly suspendTimeoutSecondsInput: number;
```

- *Type:* number

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `autoscalingLimitMaxCu`<sup>Required</sup> <a name="autoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu"></a>

```typescript
public readonly autoscalingLimitMaxCu: number;
```

- *Type:* number

---

##### `autoscalingLimitMinCu`<sup>Required</sup> <a name="autoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu"></a>

```typescript
public readonly autoscalingLimitMinCu: number;
```

- *Type:* number

---

##### `branchId`<sup>Required</sup> <a name="branchId" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchId"></a>

```typescript
public readonly branchId: string;
```

- *Type:* string

---

##### `computeProvisioner`<sup>Required</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner"></a>

```typescript
public readonly computeProvisioner: string;
```

- *Type:* string

---

##### `disabled`<sup>Required</sup> <a name="disabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabled"></a>

```typescript
public readonly disabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `pgSettings`<sup>Required</sup> <a name="pgSettings" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings"></a>

```typescript
public readonly pgSettings: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `poolerEnabled`<sup>Required</sup> <a name="poolerEnabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled"></a>

```typescript
public readonly poolerEnabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `poolerMode`<sup>Required</sup> <a name="poolerMode" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode"></a>

```typescript
public readonly poolerMode: string;
```

- *Type:* string

---

##### `projectId`<sup>Required</sup> <a name="projectId" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectId"></a>

```typescript
public readonly projectId: string;
```

- *Type:* string

---

##### `regionId`<sup>Required</sup> <a name="regionId" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionId"></a>

```typescript
public readonly regionId: string;
```

- *Type:* string

---

##### `suspendTimeoutSeconds`<sup>Required</sup> <a name="suspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds"></a>

```typescript
public readonly suspendTimeoutSeconds: number;
```

- *Type:* number

---

##### `type`<sup>Required</sup> <a name="type" id="@cdktf/provider-neon.endpoint.Endpoint.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### EndpointConfig <a name="EndpointConfig" id="@cdktf/provider-neon.endpoint.EndpointConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.endpoint.EndpointConfig.Initializer"></a>

```typescript
import { endpoint } from '@cdktf/provider-neon'

const endpointConfig: endpoint.EndpointConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId">branchId</a></code> | <code>string</code> | Branch ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId">projectId</a></code> | <code>string</code> | Project ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu">autoscalingLimitMaxCu</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu">autoscalingLimitMinCu</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner">computeProvisioner</a></code> | <code>string</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled">disabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | Disable the endpoint. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings">pgSettings</a></code> | <code>{[ key: string ]: string}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled">poolerEnabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode">poolerMode</a></code> | <code>string</code> | Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId">regionId</a></code> | <code>string</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds">suspendTimeoutSeconds</a></code> | <code>number</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.type">type</a></code> | <code>string</code> | Access type. **Note** that "read_write" is the only supported type yet. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `branchId`<sup>Required</sup> <a name="branchId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId"></a>

```typescript
public readonly branchId: string;
```

- *Type:* string

Branch ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#branch_id Endpoint#branch_id}

---

##### `projectId`<sup>Required</sup> <a name="projectId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId"></a>

```typescript
public readonly projectId: string;
```

- *Type:* string

Project ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#project_id Endpoint#project_id}

---

##### `autoscalingLimitMaxCu`<sup>Optional</sup> <a name="autoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu"></a>

```typescript
public readonly autoscalingLimitMaxCu: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}.

---

##### `autoscalingLimitMinCu`<sup>Optional</sup> <a name="autoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu"></a>

```typescript
public readonly autoscalingLimitMinCu: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}.

---

##### `computeProvisioner`<sup>Optional</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner"></a>

```typescript
public readonly computeProvisioner: string;
```

- *Type:* string

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#compute_provisioner Endpoint#compute_provisioner}

---

##### `disabled`<sup>Optional</sup> <a name="disabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled"></a>

```typescript
public readonly disabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Disable the endpoint.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#disabled Endpoint#disabled}

---

##### `pgSettings`<sup>Optional</sup> <a name="pgSettings" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings"></a>

```typescript
public readonly pgSettings: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}.

---

##### `poolerEnabled`<sup>Optional</sup> <a name="poolerEnabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled"></a>

```typescript
public readonly poolerEnabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_enabled Endpoint#pooler_enabled}

---

##### `poolerMode`<sup>Optional</sup> <a name="poolerMode" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode"></a>

```typescript
public readonly poolerMode: string;
```

- *Type:* string

Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_mode Endpoint#pooler_mode}

---

##### `regionId`<sup>Optional</sup> <a name="regionId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId"></a>

```typescript
public readonly regionId: string;
```

- *Type:* string

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#region_id Endpoint#region_id}

---

##### `suspendTimeoutSeconds`<sup>Optional</sup> <a name="suspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds"></a>

```typescript
public readonly suspendTimeoutSeconds: number;
```

- *Type:* number

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#suspend_timeout_seconds Endpoint#suspend_timeout_seconds}

---

##### `type`<sup>Optional</sup> <a name="type" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Access type. **Note** that "read_write" is the only supported type yet.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#type Endpoint#type}

---



