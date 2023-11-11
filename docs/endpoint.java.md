# `neon_endpoint`

Refer to the Terraform Registory for docs: [`neon_endpoint`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint).

# `endpoint` Submodule <a name="`endpoint` Submodule" id="@cdktf/provider-neon.endpoint"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Endpoint <a name="Endpoint" id="@cdktf/provider-neon.endpoint.Endpoint"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint neon_endpoint}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.endpoint.Endpoint;

Endpoint.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection)
//  .connection(WinrmProvisionerConnection)
//  .count(java.lang.Number)
//  .count(TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner)
//  .provisioners(LocalExecProvisioner)
//  .provisioners(RemoteExecProvisioner>)
    .branchId(java.lang.String)
    .projectId(java.lang.String)
//  .autoscalingLimitMaxCu(java.lang.Number)
//  .autoscalingLimitMinCu(java.lang.Number)
//  .computeProvisioner(java.lang.String)
//  .disabled(java.lang.Boolean)
//  .disabled(IResolvable)
//  .pgSettings(java.util.Map<java.lang.String, java.lang.String>)
//  .poolerEnabled(java.lang.Boolean)
//  .poolerEnabled(IResolvable)
//  .poolerMode(java.lang.String)
//  .regionId(java.lang.String)
//  .suspendTimeoutSeconds(java.lang.Number)
//  .type(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.branchId">branchId</a></code> | <code>java.lang.String</code> | Branch ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.projectId">projectId</a></code> | <code>java.lang.String</code> | Project ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.autoscalingLimitMaxCu">autoscalingLimitMaxCu</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.autoscalingLimitMinCu">autoscalingLimitMinCu</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.computeProvisioner">computeProvisioner</a></code> | <code>java.lang.String</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.disabled">disabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Disable the endpoint. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.pgSettings">pgSettings</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.poolerEnabled">poolerEnabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.poolerMode">poolerMode</a></code> | <code>java.lang.String</code> | Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.regionId">regionId</a></code> | <code>java.lang.String</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.suspendTimeoutSeconds">suspendTimeoutSeconds</a></code> | <code>java.lang.Number</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.type">type</a></code> | <code>java.lang.String</code> | Access type. **Note** that "read_write" is the only supported type yet. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.connection"></a>

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.count"></a>

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.forEach"></a>

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.lifecycle"></a>

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `branchId`<sup>Required</sup> <a name="branchId" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.branchId"></a>

- *Type:* java.lang.String

Branch ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#branch_id Endpoint#branch_id}

---

##### `projectId`<sup>Required</sup> <a name="projectId" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.projectId"></a>

- *Type:* java.lang.String

Project ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#project_id Endpoint#project_id}

---

##### `autoscalingLimitMaxCu`<sup>Optional</sup> <a name="autoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.autoscalingLimitMaxCu"></a>

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}.

---

##### `autoscalingLimitMinCu`<sup>Optional</sup> <a name="autoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.autoscalingLimitMinCu"></a>

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}.

---

##### `computeProvisioner`<sup>Optional</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.computeProvisioner"></a>

- *Type:* java.lang.String

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#compute_provisioner Endpoint#compute_provisioner}

---

##### `disabled`<sup>Optional</sup> <a name="disabled" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.disabled"></a>

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Disable the endpoint.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#disabled Endpoint#disabled}

---

##### `pgSettings`<sup>Optional</sup> <a name="pgSettings" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.pgSettings"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}.

---

##### `poolerEnabled`<sup>Optional</sup> <a name="poolerEnabled" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.poolerEnabled"></a>

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_enabled Endpoint#pooler_enabled}

---

##### `poolerMode`<sup>Optional</sup> <a name="poolerMode" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.poolerMode"></a>

- *Type:* java.lang.String

Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_mode Endpoint#pooler_mode}

---

##### `regionId`<sup>Optional</sup> <a name="regionId" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.regionId"></a>

- *Type:* java.lang.String

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#region_id Endpoint#region_id}

---

##### `suspendTimeoutSeconds`<sup>Optional</sup> <a name="suspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.suspendTimeoutSeconds"></a>

- *Type:* java.lang.Number

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#suspend_timeout_seconds Endpoint#suspend_timeout_seconds}

---

##### `type`<sup>Optional</sup> <a name="type" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.type"></a>

- *Type:* java.lang.String

Access type. **Note** that "read_write" is the only supported type yet.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#type Endpoint#type}

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

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktf/provider-neon.endpoint.Endpoint.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="@cdktf/provider-neon.endpoint.Endpoint.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktf/provider-neon.endpoint.Endpoint.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget"></a>

```java
public void addMoveTarget(java.lang.String moveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget.parameter.moveTarget"></a>

- *Type:* java.lang.String

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `importFrom` <a name="importFrom" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom"></a>

```java
public void importFrom(java.lang.String id)
public void importFrom(java.lang.String id, TerraformProvider provider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.id"></a>

- *Type:* java.lang.String

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `moveTo` <a name="moveTo" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo"></a>

```java
public void moveTo(java.lang.String moveTarget)
public void moveTo(java.lang.String moveTarget, java.lang.String OR java.lang.Number index)
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.moveTarget"></a>

- *Type:* java.lang.String

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.index"></a>

- *Type:* java.lang.String OR java.lang.Number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `resetAutoscalingLimitMaxCu` <a name="resetAutoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMaxCu"></a>

```java
public void resetAutoscalingLimitMaxCu()
```

##### `resetAutoscalingLimitMinCu` <a name="resetAutoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMinCu"></a>

```java
public void resetAutoscalingLimitMinCu()
```

##### `resetComputeProvisioner` <a name="resetComputeProvisioner" id="@cdktf/provider-neon.endpoint.Endpoint.resetComputeProvisioner"></a>

```java
public void resetComputeProvisioner()
```

##### `resetDisabled` <a name="resetDisabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetDisabled"></a>

```java
public void resetDisabled()
```

##### `resetPgSettings` <a name="resetPgSettings" id="@cdktf/provider-neon.endpoint.Endpoint.resetPgSettings"></a>

```java
public void resetPgSettings()
```

##### `resetPoolerEnabled` <a name="resetPoolerEnabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerEnabled"></a>

```java
public void resetPoolerEnabled()
```

##### `resetPoolerMode` <a name="resetPoolerMode" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerMode"></a>

```java
public void resetPoolerMode()
```

##### `resetRegionId` <a name="resetRegionId" id="@cdktf/provider-neon.endpoint.Endpoint.resetRegionId"></a>

```java
public void resetRegionId()
```

##### `resetSuspendTimeoutSeconds` <a name="resetSuspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.Endpoint.resetSuspendTimeoutSeconds"></a>

```java
public void resetSuspendTimeoutSeconds()
```

##### `resetType` <a name="resetType" id="@cdktf/provider-neon.endpoint.Endpoint.resetType"></a>

```java
public void resetType()
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

```java
import com.hashicorp.cdktf.providers.neon.endpoint.Endpoint;

Endpoint.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement"></a>

```java
import com.hashicorp.cdktf.providers.neon.endpoint.Endpoint;

Endpoint.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource"></a>

```java
import com.hashicorp.cdktf.providers.neon.endpoint.Endpoint;

Endpoint.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport"></a>

```java
import com.hashicorp.cdktf.providers.neon.endpoint.Endpoint;

Endpoint.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),Endpoint.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTF code for importing a Endpoint resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the Endpoint to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing Endpoint that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

? Optional instance of the provider where the Endpoint to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack">cdktfStack</a></code> | <code>com.hashicorp.cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>com.hashicorp.cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.host">host</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost">proxyHost</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput">autoscalingLimitMaxCuInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput">autoscalingLimitMinCuInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput">branchIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput">computeProvisionerInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput">disabledInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput">pgSettingsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput">poolerEnabledInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput">poolerModeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput">projectIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput">regionIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput">suspendTimeoutSecondsInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu">autoscalingLimitMaxCu</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu">autoscalingLimitMinCu</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchId">branchId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner">computeProvisioner</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabled">disabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings">pgSettings</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled">poolerEnabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode">poolerMode</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectId">projectId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionId">regionId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds">suspendTimeoutSeconds</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-neon.endpoint.Endpoint.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* com.hashicorp.cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.endpoint.Endpoint.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* com.hashicorp.cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.endpoint.Endpoint.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.endpoint.Endpoint.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.endpoint.Endpoint.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.endpoint.Endpoint.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `host`<sup>Required</sup> <a name="host" id="@cdktf/provider-neon.endpoint.Endpoint.property.host"></a>

```java
public java.lang.String getHost();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `proxyHost`<sup>Required</sup> <a name="proxyHost" id="@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost"></a>

```java
public java.lang.String getProxyHost();
```

- *Type:* java.lang.String

---

##### `autoscalingLimitMaxCuInput`<sup>Optional</sup> <a name="autoscalingLimitMaxCuInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput"></a>

```java
public java.lang.Number getAutoscalingLimitMaxCuInput();
```

- *Type:* java.lang.Number

---

##### `autoscalingLimitMinCuInput`<sup>Optional</sup> <a name="autoscalingLimitMinCuInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput"></a>

```java
public java.lang.Number getAutoscalingLimitMinCuInput();
```

- *Type:* java.lang.Number

---

##### `branchIdInput`<sup>Optional</sup> <a name="branchIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput"></a>

```java
public java.lang.String getBranchIdInput();
```

- *Type:* java.lang.String

---

##### `computeProvisionerInput`<sup>Optional</sup> <a name="computeProvisionerInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput"></a>

```java
public java.lang.String getComputeProvisionerInput();
```

- *Type:* java.lang.String

---

##### `disabledInput`<sup>Optional</sup> <a name="disabledInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput"></a>

```java
public java.lang.Object getDisabledInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `pgSettingsInput`<sup>Optional</sup> <a name="pgSettingsInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getPgSettingsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `poolerEnabledInput`<sup>Optional</sup> <a name="poolerEnabledInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput"></a>

```java
public java.lang.Object getPoolerEnabledInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `poolerModeInput`<sup>Optional</sup> <a name="poolerModeInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput"></a>

```java
public java.lang.String getPoolerModeInput();
```

- *Type:* java.lang.String

---

##### `projectIdInput`<sup>Optional</sup> <a name="projectIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput"></a>

```java
public java.lang.String getProjectIdInput();
```

- *Type:* java.lang.String

---

##### `regionIdInput`<sup>Optional</sup> <a name="regionIdInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput"></a>

```java
public java.lang.String getRegionIdInput();
```

- *Type:* java.lang.String

---

##### `suspendTimeoutSecondsInput`<sup>Optional</sup> <a name="suspendTimeoutSecondsInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput"></a>

```java
public java.lang.Number getSuspendTimeoutSecondsInput();
```

- *Type:* java.lang.Number

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="@cdktf/provider-neon.endpoint.Endpoint.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `autoscalingLimitMaxCu`<sup>Required</sup> <a name="autoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu"></a>

```java
public java.lang.Number getAutoscalingLimitMaxCu();
```

- *Type:* java.lang.Number

---

##### `autoscalingLimitMinCu`<sup>Required</sup> <a name="autoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu"></a>

```java
public java.lang.Number getAutoscalingLimitMinCu();
```

- *Type:* java.lang.Number

---

##### `branchId`<sup>Required</sup> <a name="branchId" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchId"></a>

```java
public java.lang.String getBranchId();
```

- *Type:* java.lang.String

---

##### `computeProvisioner`<sup>Required</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner"></a>

```java
public java.lang.String getComputeProvisioner();
```

- *Type:* java.lang.String

---

##### `disabled`<sup>Required</sup> <a name="disabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabled"></a>

```java
public java.lang.Object getDisabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `pgSettings`<sup>Required</sup> <a name="pgSettings" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getPgSettings();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `poolerEnabled`<sup>Required</sup> <a name="poolerEnabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled"></a>

```java
public java.lang.Object getPoolerEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `poolerMode`<sup>Required</sup> <a name="poolerMode" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode"></a>

```java
public java.lang.String getPoolerMode();
```

- *Type:* java.lang.String

---

##### `projectId`<sup>Required</sup> <a name="projectId" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectId"></a>

```java
public java.lang.String getProjectId();
```

- *Type:* java.lang.String

---

##### `regionId`<sup>Required</sup> <a name="regionId" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionId"></a>

```java
public java.lang.String getRegionId();
```

- *Type:* java.lang.String

---

##### `suspendTimeoutSeconds`<sup>Required</sup> <a name="suspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds"></a>

```java
public java.lang.Number getSuspendTimeoutSeconds();
```

- *Type:* java.lang.Number

---

##### `type`<sup>Required</sup> <a name="type" id="@cdktf/provider-neon.endpoint.Endpoint.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### EndpointConfig <a name="EndpointConfig" id="@cdktf/provider-neon.endpoint.EndpointConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.endpoint.EndpointConfig.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.endpoint.EndpointConfig;

EndpointConfig.builder()
//  .connection(SSHProvisionerConnection)
//  .connection(WinrmProvisionerConnection)
//  .count(java.lang.Number)
//  .count(TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner)
//  .provisioners(LocalExecProvisioner)
//  .provisioners(RemoteExecProvisioner>)
    .branchId(java.lang.String)
    .projectId(java.lang.String)
//  .autoscalingLimitMaxCu(java.lang.Number)
//  .autoscalingLimitMinCu(java.lang.Number)
//  .computeProvisioner(java.lang.String)
//  .disabled(java.lang.Boolean)
//  .disabled(IResolvable)
//  .pgSettings(java.util.Map<java.lang.String, java.lang.String>)
//  .poolerEnabled(java.lang.Boolean)
//  .poolerEnabled(IResolvable)
//  .poolerMode(java.lang.String)
//  .regionId(java.lang.String)
//  .suspendTimeoutSeconds(java.lang.Number)
//  .type(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId">branchId</a></code> | <code>java.lang.String</code> | Branch ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId">projectId</a></code> | <code>java.lang.String</code> | Project ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu">autoscalingLimitMaxCu</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu">autoscalingLimitMinCu</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner">computeProvisioner</a></code> | <code>java.lang.String</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled">disabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Disable the endpoint. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings">pgSettings</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled">poolerEnabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode">poolerMode</a></code> | <code>java.lang.String</code> | Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId">regionId</a></code> | <code>java.lang.String</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds">suspendTimeoutSeconds</a></code> | <code>java.lang.Number</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.type">type</a></code> | <code>java.lang.String</code> | Access type. **Note** that "read_write" is the only supported type yet. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `branchId`<sup>Required</sup> <a name="branchId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId"></a>

```java
public java.lang.String getBranchId();
```

- *Type:* java.lang.String

Branch ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#branch_id Endpoint#branch_id}

---

##### `projectId`<sup>Required</sup> <a name="projectId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId"></a>

```java
public java.lang.String getProjectId();
```

- *Type:* java.lang.String

Project ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#project_id Endpoint#project_id}

---

##### `autoscalingLimitMaxCu`<sup>Optional</sup> <a name="autoscalingLimitMaxCu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu"></a>

```java
public java.lang.Number getAutoscalingLimitMaxCu();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}.

---

##### `autoscalingLimitMinCu`<sup>Optional</sup> <a name="autoscalingLimitMinCu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu"></a>

```java
public java.lang.Number getAutoscalingLimitMinCu();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}.

---

##### `computeProvisioner`<sup>Optional</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner"></a>

```java
public java.lang.String getComputeProvisioner();
```

- *Type:* java.lang.String

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#compute_provisioner Endpoint#compute_provisioner}

---

##### `disabled`<sup>Optional</sup> <a name="disabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled"></a>

```java
public java.lang.Object getDisabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Disable the endpoint.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#disabled Endpoint#disabled}

---

##### `pgSettings`<sup>Optional</sup> <a name="pgSettings" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getPgSettings();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}.

---

##### `poolerEnabled`<sup>Optional</sup> <a name="poolerEnabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled"></a>

```java
public java.lang.Object getPoolerEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_enabled Endpoint#pooler_enabled}

---

##### `poolerMode`<sup>Optional</sup> <a name="poolerMode" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode"></a>

```java
public java.lang.String getPoolerMode();
```

- *Type:* java.lang.String

Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_mode Endpoint#pooler_mode}

---

##### `regionId`<sup>Optional</sup> <a name="regionId" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId"></a>

```java
public java.lang.String getRegionId();
```

- *Type:* java.lang.String

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#region_id Endpoint#region_id}

---

##### `suspendTimeoutSeconds`<sup>Optional</sup> <a name="suspendTimeoutSeconds" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds"></a>

```java
public java.lang.Number getSuspendTimeoutSeconds();
```

- *Type:* java.lang.Number

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#suspend_timeout_seconds Endpoint#suspend_timeout_seconds}

---

##### `type`<sup>Optional</sup> <a name="type" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Access type. **Note** that "read_write" is the only supported type yet.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#type Endpoint#type}

---



