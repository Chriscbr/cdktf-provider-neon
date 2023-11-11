# `neon_project`

Refer to the Terraform Registory for docs: [`neon_project`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project).

# `project` Submodule <a name="`project` Submodule" id="@cdktf/provider-neon.project"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Project <a name="Project" id="@cdktf/provider-neon.project.Project"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project neon_project}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.Project.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.Project;

Project.Builder.create(Construct scope, java.lang.String id)
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
//  .branch(ProjectBranch)
//  .computeProvisioner(java.lang.String)
//  .defaultEndpointSettings(ProjectDefaultEndpointSettings)
//  .historyRetentionSeconds(java.lang.Number)
//  .name(java.lang.String)
//  .pgVersion(java.lang.Number)
//  .quota(ProjectQuota)
//  .regionId(java.lang.String)
//  .storePassword(java.lang.Boolean)
//  .storePassword(IResolvable)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.branch">branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | branch block. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.computeProvisioner">computeProvisioner</a></code> | <code>java.lang.String</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.defaultEndpointSettings">defaultEndpointSettings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | default_endpoint_settings block. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.historyRetentionSeconds">historyRetentionSeconds</a></code> | <code>java.lang.Number</code> | The number of seconds to retain the point-in-time restore (PITR) backup history for this project. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | Project name. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.pgVersion">pgVersion</a></code> | <code>java.lang.Number</code> | Postgres version. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.quota">quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | quota block. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.regionId">regionId</a></code> | <code>java.lang.String</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.storePassword">storePassword</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Whether or not passwords are stored for roles in the Neon project. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.project.Project.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.project.Project.Initializer.parameter.connection"></a>

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.project.Project.Initializer.parameter.count"></a>

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.project.Project.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.project.Project.Initializer.parameter.forEach"></a>

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.project.Project.Initializer.parameter.lifecycle"></a>

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.Initializer.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.project.Project.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `branch`<sup>Optional</sup> <a name="branch" id="@cdktf/provider-neon.project.Project.Initializer.parameter.branch"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

branch block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#branch Project#branch}

---

##### `computeProvisioner`<sup>Optional</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.project.Project.Initializer.parameter.computeProvisioner"></a>

- *Type:* java.lang.String

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_provisioner Project#compute_provisioner}

---

##### `defaultEndpointSettings`<sup>Optional</sup> <a name="defaultEndpointSettings" id="@cdktf/provider-neon.project.Project.Initializer.parameter.defaultEndpointSettings"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

default_endpoint_settings block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#default_endpoint_settings Project#default_endpoint_settings}

---

##### `historyRetentionSeconds`<sup>Optional</sup> <a name="historyRetentionSeconds" id="@cdktf/provider-neon.project.Project.Initializer.parameter.historyRetentionSeconds"></a>

- *Type:* java.lang.Number

The number of seconds to retain the point-in-time restore (PITR) backup history for this project.

Default: 7 days, see https://neon.tech/docs/reference/glossary#point-in-time-restore.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#history_retention_seconds Project#history_retention_seconds}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktf/provider-neon.project.Project.Initializer.parameter.name"></a>

- *Type:* java.lang.String

Project name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `pgVersion`<sup>Optional</sup> <a name="pgVersion" id="@cdktf/provider-neon.project.Project.Initializer.parameter.pgVersion"></a>

- *Type:* java.lang.Number

Postgres version.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#pg_version Project#pg_version}

---

##### `quota`<sup>Optional</sup> <a name="quota" id="@cdktf/provider-neon.project.Project.Initializer.parameter.quota"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

quota block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#quota Project#quota}

---

##### `regionId`<sup>Optional</sup> <a name="regionId" id="@cdktf/provider-neon.project.Project.Initializer.parameter.regionId"></a>

- *Type:* java.lang.String

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#region_id Project#region_id}

---

##### `storePassword`<sup>Optional</sup> <a name="storePassword" id="@cdktf/provider-neon.project.Project.Initializer.parameter.storePassword"></a>

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Whether or not passwords are stored for roles in the Neon project.

Storing passwords facilitates access to Neon features that require authorization.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#store_password Project#store_password}

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

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="@cdktf/provider-neon.project.Project.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-neon.project.Project.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktf/provider-neon.project.Project.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktf/provider-neon.project.Project.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktf/provider-neon.project.Project.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="@cdktf/provider-neon.project.Project.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktf/provider-neon.project.Project.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktf/provider-neon.project.Project.addMoveTarget"></a>

```java
public void addMoveTarget(java.lang.String moveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.project.Project.addMoveTarget.parameter.moveTarget"></a>

- *Type:* java.lang.String

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.project.Project.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.project.Project.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `importFrom` <a name="importFrom" id="@cdktf/provider-neon.project.Project.importFrom"></a>

```java
public void importFrom(java.lang.String id)
public void importFrom(java.lang.String id, TerraformProvider provider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.importFrom.parameter.id"></a>

- *Type:* java.lang.String

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.importFrom.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `moveTo` <a name="moveTo" id="@cdktf/provider-neon.project.Project.moveTo"></a>

```java
public void moveTo(java.lang.String moveTarget)
public void moveTo(java.lang.String moveTarget, java.lang.String OR java.lang.Number index)
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktf/provider-neon.project.Project.moveTo.parameter.moveTarget"></a>

- *Type:* java.lang.String

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-neon.project.Project.moveTo.parameter.index"></a>

- *Type:* java.lang.String OR java.lang.Number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `putBranch` <a name="putBranch" id="@cdktf/provider-neon.project.Project.putBranch"></a>

```java
public void putBranch(ProjectBranch value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.putBranch.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---

##### `putDefaultEndpointSettings` <a name="putDefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings"></a>

```java
public void putDefaultEndpointSettings(ProjectDefaultEndpointSettings value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---

##### `putQuota` <a name="putQuota" id="@cdktf/provider-neon.project.Project.putQuota"></a>

```java
public void putQuota(ProjectQuota value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.putQuota.parameter.value"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---

##### `resetBranch` <a name="resetBranch" id="@cdktf/provider-neon.project.Project.resetBranch"></a>

```java
public void resetBranch()
```

##### `resetComputeProvisioner` <a name="resetComputeProvisioner" id="@cdktf/provider-neon.project.Project.resetComputeProvisioner"></a>

```java
public void resetComputeProvisioner()
```

##### `resetDefaultEndpointSettings` <a name="resetDefaultEndpointSettings" id="@cdktf/provider-neon.project.Project.resetDefaultEndpointSettings"></a>

```java
public void resetDefaultEndpointSettings()
```

##### `resetHistoryRetentionSeconds` <a name="resetHistoryRetentionSeconds" id="@cdktf/provider-neon.project.Project.resetHistoryRetentionSeconds"></a>

```java
public void resetHistoryRetentionSeconds()
```

##### `resetName` <a name="resetName" id="@cdktf/provider-neon.project.Project.resetName"></a>

```java
public void resetName()
```

##### `resetPgVersion` <a name="resetPgVersion" id="@cdktf/provider-neon.project.Project.resetPgVersion"></a>

```java
public void resetPgVersion()
```

##### `resetQuota` <a name="resetQuota" id="@cdktf/provider-neon.project.Project.resetQuota"></a>

```java
public void resetQuota()
```

##### `resetRegionId` <a name="resetRegionId" id="@cdktf/provider-neon.project.Project.resetRegionId"></a>

```java
public void resetRegionId()
```

##### `resetStorePassword` <a name="resetStorePassword" id="@cdktf/provider-neon.project.Project.resetStorePassword"></a>

```java
public void resetStorePassword()
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

```java
import com.hashicorp.cdktf.providers.neon.project.Project;

Project.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktf/provider-neon.project.Project.isTerraformElement"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.Project;

Project.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.project.Project.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktf/provider-neon.project.Project.isTerraformResource"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.Project;

Project.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.project.Project.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktf/provider-neon.project.Project.generateConfigForImport"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.Project;

Project.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),Project.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTF code for importing a Project resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the Project to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing Project that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

? Optional instance of the provider where the Project to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktf/provider-neon.project.Project.property.cdktfStack">cdktfStack</a></code> | <code>com.hashicorp.cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>com.hashicorp.cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branch">branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connectionUri">connectionUri</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseHost">databaseHost</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseName">databaseName</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databasePassword">databasePassword</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseUser">databaseUser</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultBranchId">defaultBranchId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettings">defaultEndpointSettings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quota">quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branchInput">branchInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisionerInput">computeProvisionerInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput">defaultEndpointSettingsInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput">historyRetentionSecondsInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersionInput">pgVersionInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quotaInput">quotaInput</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionIdInput">regionIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePasswordInput">storePasswordInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisioner">computeProvisioner</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSeconds">historyRetentionSeconds</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersion">pgVersion</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionId">regionId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePassword">storePassword</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-neon.project.Project.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktf/provider-neon.project.Project.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* com.hashicorp.cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.Project.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktf/provider-neon.project.Project.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktf/provider-neon.project.Project.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktf/provider-neon.project.Project.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* com.hashicorp.cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.project.Project.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.project.Project.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.project.Project.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.project.Project.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.project.Project.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.project.Project.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `branch`<sup>Required</sup> <a name="branch" id="@cdktf/provider-neon.project.Project.property.branch"></a>

```java
public ProjectBranchOutputReference getBranch();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a>

---

##### `connectionUri`<sup>Required</sup> <a name="connectionUri" id="@cdktf/provider-neon.project.Project.property.connectionUri"></a>

```java
public java.lang.String getConnectionUri();
```

- *Type:* java.lang.String

---

##### `databaseHost`<sup>Required</sup> <a name="databaseHost" id="@cdktf/provider-neon.project.Project.property.databaseHost"></a>

```java
public java.lang.String getDatabaseHost();
```

- *Type:* java.lang.String

---

##### `databaseName`<sup>Required</sup> <a name="databaseName" id="@cdktf/provider-neon.project.Project.property.databaseName"></a>

```java
public java.lang.String getDatabaseName();
```

- *Type:* java.lang.String

---

##### `databasePassword`<sup>Required</sup> <a name="databasePassword" id="@cdktf/provider-neon.project.Project.property.databasePassword"></a>

```java
public java.lang.String getDatabasePassword();
```

- *Type:* java.lang.String

---

##### `databaseUser`<sup>Required</sup> <a name="databaseUser" id="@cdktf/provider-neon.project.Project.property.databaseUser"></a>

```java
public java.lang.String getDatabaseUser();
```

- *Type:* java.lang.String

---

##### `defaultBranchId`<sup>Required</sup> <a name="defaultBranchId" id="@cdktf/provider-neon.project.Project.property.defaultBranchId"></a>

```java
public java.lang.String getDefaultBranchId();
```

- *Type:* java.lang.String

---

##### `defaultEndpointSettings`<sup>Required</sup> <a name="defaultEndpointSettings" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettings"></a>

```java
public ProjectDefaultEndpointSettingsOutputReference getDefaultEndpointSettings();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a>

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `quota`<sup>Required</sup> <a name="quota" id="@cdktf/provider-neon.project.Project.property.quota"></a>

```java
public ProjectQuotaOutputReference getQuota();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a>

---

##### `branchInput`<sup>Optional</sup> <a name="branchInput" id="@cdktf/provider-neon.project.Project.property.branchInput"></a>

```java
public ProjectBranch getBranchInput();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---

##### `computeProvisionerInput`<sup>Optional</sup> <a name="computeProvisionerInput" id="@cdktf/provider-neon.project.Project.property.computeProvisionerInput"></a>

```java
public java.lang.String getComputeProvisionerInput();
```

- *Type:* java.lang.String

---

##### `defaultEndpointSettingsInput`<sup>Optional</sup> <a name="defaultEndpointSettingsInput" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput"></a>

```java
public ProjectDefaultEndpointSettings getDefaultEndpointSettingsInput();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---

##### `historyRetentionSecondsInput`<sup>Optional</sup> <a name="historyRetentionSecondsInput" id="@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput"></a>

```java
public java.lang.Number getHistoryRetentionSecondsInput();
```

- *Type:* java.lang.Number

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktf/provider-neon.project.Project.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `pgVersionInput`<sup>Optional</sup> <a name="pgVersionInput" id="@cdktf/provider-neon.project.Project.property.pgVersionInput"></a>

```java
public java.lang.Number getPgVersionInput();
```

- *Type:* java.lang.Number

---

##### `quotaInput`<sup>Optional</sup> <a name="quotaInput" id="@cdktf/provider-neon.project.Project.property.quotaInput"></a>

```java
public ProjectQuota getQuotaInput();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---

##### `regionIdInput`<sup>Optional</sup> <a name="regionIdInput" id="@cdktf/provider-neon.project.Project.property.regionIdInput"></a>

```java
public java.lang.String getRegionIdInput();
```

- *Type:* java.lang.String

---

##### `storePasswordInput`<sup>Optional</sup> <a name="storePasswordInput" id="@cdktf/provider-neon.project.Project.property.storePasswordInput"></a>

```java
public java.lang.Object getStorePasswordInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `computeProvisioner`<sup>Required</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.project.Project.property.computeProvisioner"></a>

```java
public java.lang.String getComputeProvisioner();
```

- *Type:* java.lang.String

---

##### `historyRetentionSeconds`<sup>Required</sup> <a name="historyRetentionSeconds" id="@cdktf/provider-neon.project.Project.property.historyRetentionSeconds"></a>

```java
public java.lang.Number getHistoryRetentionSeconds();
```

- *Type:* java.lang.Number

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktf/provider-neon.project.Project.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `pgVersion`<sup>Required</sup> <a name="pgVersion" id="@cdktf/provider-neon.project.Project.property.pgVersion"></a>

```java
public java.lang.Number getPgVersion();
```

- *Type:* java.lang.Number

---

##### `regionId`<sup>Required</sup> <a name="regionId" id="@cdktf/provider-neon.project.Project.property.regionId"></a>

```java
public java.lang.String getRegionId();
```

- *Type:* java.lang.String

---

##### `storePassword`<sup>Required</sup> <a name="storePassword" id="@cdktf/provider-neon.project.Project.property.storePassword"></a>

```java
public java.lang.Object getStorePassword();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-neon.project.Project.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### ProjectBranch <a name="ProjectBranch" id="@cdktf/provider-neon.project.ProjectBranch"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectBranch.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.ProjectBranch;

ProjectBranch.builder()
//  .databaseName(java.lang.String)
//  .name(java.lang.String)
//  .roleName(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.databaseName">databaseName</a></code> | <code>java.lang.String</code> | The database name. If not specified, the default database name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.name">name</a></code> | <code>java.lang.String</code> | The branch name. If not specified, the default branch name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.roleName">roleName</a></code> | <code>java.lang.String</code> | The role name. If not specified, the default role name will be used. |

---

##### `databaseName`<sup>Optional</sup> <a name="databaseName" id="@cdktf/provider-neon.project.ProjectBranch.property.databaseName"></a>

```java
public java.lang.String getDatabaseName();
```

- *Type:* java.lang.String

The database name. If not specified, the default database name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#database_name Project#database_name}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktf/provider-neon.project.ProjectBranch.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

The branch name. If not specified, the default branch name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `roleName`<sup>Optional</sup> <a name="roleName" id="@cdktf/provider-neon.project.ProjectBranch.property.roleName"></a>

```java
public java.lang.String getRoleName();
```

- *Type:* java.lang.String

The role name. If not specified, the default role name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#role_name Project#role_name}

---

### ProjectConfig <a name="ProjectConfig" id="@cdktf/provider-neon.project.ProjectConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectConfig.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.ProjectConfig;

ProjectConfig.builder()
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
//  .branch(ProjectBranch)
//  .computeProvisioner(java.lang.String)
//  .defaultEndpointSettings(ProjectDefaultEndpointSettings)
//  .historyRetentionSeconds(java.lang.Number)
//  .name(java.lang.String)
//  .pgVersion(java.lang.Number)
//  .quota(ProjectQuota)
//  .regionId(java.lang.String)
//  .storePassword(java.lang.Boolean)
//  .storePassword(IResolvable)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.branch">branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | branch block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner">computeProvisioner</a></code> | <code>java.lang.String</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings">defaultEndpointSettings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | default_endpoint_settings block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds">historyRetentionSeconds</a></code> | <code>java.lang.Number</code> | The number of seconds to retain the point-in-time restore (PITR) backup history for this project. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.name">name</a></code> | <code>java.lang.String</code> | Project name. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.pgVersion">pgVersion</a></code> | <code>java.lang.Number</code> | Postgres version. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.quota">quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | quota block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.regionId">regionId</a></code> | <code>java.lang.String</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.storePassword">storePassword</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Whether or not passwords are stored for roles in the Neon project. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.project.ProjectConfig.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.project.ProjectConfig.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktf/provider-neon.project.ProjectConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktf/provider-neon.project.ProjectConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.project.ProjectConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.ProjectConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.project.ProjectConfig.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `branch`<sup>Optional</sup> <a name="branch" id="@cdktf/provider-neon.project.ProjectConfig.property.branch"></a>

```java
public ProjectBranch getBranch();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

branch block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#branch Project#branch}

---

##### `computeProvisioner`<sup>Optional</sup> <a name="computeProvisioner" id="@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner"></a>

```java
public java.lang.String getComputeProvisioner();
```

- *Type:* java.lang.String

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_provisioner Project#compute_provisioner}

---

##### `defaultEndpointSettings`<sup>Optional</sup> <a name="defaultEndpointSettings" id="@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings"></a>

```java
public ProjectDefaultEndpointSettings getDefaultEndpointSettings();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

default_endpoint_settings block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#default_endpoint_settings Project#default_endpoint_settings}

---

##### `historyRetentionSeconds`<sup>Optional</sup> <a name="historyRetentionSeconds" id="@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds"></a>

```java
public java.lang.Number getHistoryRetentionSeconds();
```

- *Type:* java.lang.Number

The number of seconds to retain the point-in-time restore (PITR) backup history for this project.

Default: 7 days, see https://neon.tech/docs/reference/glossary#point-in-time-restore.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#history_retention_seconds Project#history_retention_seconds}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktf/provider-neon.project.ProjectConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

Project name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `pgVersion`<sup>Optional</sup> <a name="pgVersion" id="@cdktf/provider-neon.project.ProjectConfig.property.pgVersion"></a>

```java
public java.lang.Number getPgVersion();
```

- *Type:* java.lang.Number

Postgres version.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#pg_version Project#pg_version}

---

##### `quota`<sup>Optional</sup> <a name="quota" id="@cdktf/provider-neon.project.ProjectConfig.property.quota"></a>

```java
public ProjectQuota getQuota();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

quota block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#quota Project#quota}

---

##### `regionId`<sup>Optional</sup> <a name="regionId" id="@cdktf/provider-neon.project.ProjectConfig.property.regionId"></a>

```java
public java.lang.String getRegionId();
```

- *Type:* java.lang.String

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#region_id Project#region_id}

---

##### `storePassword`<sup>Optional</sup> <a name="storePassword" id="@cdktf/provider-neon.project.ProjectConfig.property.storePassword"></a>

```java
public java.lang.Object getStorePassword();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Whether or not passwords are stored for roles in the Neon project.

Storing passwords facilitates access to Neon features that require authorization.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#store_password Project#store_password}

---

### ProjectDefaultEndpointSettings <a name="ProjectDefaultEndpointSettings" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.ProjectDefaultEndpointSettings;

ProjectDefaultEndpointSettings.builder()
//  .autoscalingLimitMaxCu(java.lang.Number)
//  .autoscalingLimitMinCu(java.lang.Number)
//  .suspendTimeoutSeconds(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu">autoscalingLimitMaxCu</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu">autoscalingLimitMinCu</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds">suspendTimeoutSeconds</a></code> | <code>java.lang.Number</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |

---

##### `autoscalingLimitMaxCu`<sup>Optional</sup> <a name="autoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu"></a>

```java
public java.lang.Number getAutoscalingLimitMaxCu();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}.

---

##### `autoscalingLimitMinCu`<sup>Optional</sup> <a name="autoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu"></a>

```java
public java.lang.Number getAutoscalingLimitMinCu();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}.

---

##### `suspendTimeoutSeconds`<sup>Optional</sup> <a name="suspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds"></a>

```java
public java.lang.Number getSuspendTimeoutSeconds();
```

- *Type:* java.lang.Number

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#suspend_timeout_seconds Project#suspend_timeout_seconds}

---

### ProjectQuota <a name="ProjectQuota" id="@cdktf/provider-neon.project.ProjectQuota"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectQuota.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.ProjectQuota;

ProjectQuota.builder()
//  .activeTimeSeconds(java.lang.Number)
//  .computeTimeSeconds(java.lang.Number)
//  .dataTransferBytes(java.lang.Number)
//  .logicalSizeBytes(java.lang.Number)
//  .writtenDataBytes(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds">activeTimeSeconds</a></code> | <code>java.lang.Number</code> | The total amount of wall-clock time allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds">computeTimeSeconds</a></code> | <code>java.lang.Number</code> | The total amount of CPU seconds allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes">dataTransferBytes</a></code> | <code>java.lang.Number</code> | Total amount of data transferred from all of a project's branches using the proxy. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes">logicalSizeBytes</a></code> | <code>java.lang.Number</code> | Limit on the logical size of every project's branch. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes">writtenDataBytes</a></code> | <code>java.lang.Number</code> | Total amount of data written to all of a project's branches. |

---

##### `activeTimeSeconds`<sup>Optional</sup> <a name="activeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds"></a>

```java
public java.lang.Number getActiveTimeSeconds();
```

- *Type:* java.lang.Number

The total amount of wall-clock time allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#active_time_seconds Project#active_time_seconds}

---

##### `computeTimeSeconds`<sup>Optional</sup> <a name="computeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds"></a>

```java
public java.lang.Number getComputeTimeSeconds();
```

- *Type:* java.lang.Number

The total amount of CPU seconds allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_time_seconds Project#compute_time_seconds}

---

##### `dataTransferBytes`<sup>Optional</sup> <a name="dataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes"></a>

```java
public java.lang.Number getDataTransferBytes();
```

- *Type:* java.lang.Number

Total amount of data transferred from all of a project's branches using the proxy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#data_transfer_bytes Project#data_transfer_bytes}

---

##### `logicalSizeBytes`<sup>Optional</sup> <a name="logicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes"></a>

```java
public java.lang.Number getLogicalSizeBytes();
```

- *Type:* java.lang.Number

Limit on the logical size of every project's branch.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#logical_size_bytes Project#logical_size_bytes}

---

##### `writtenDataBytes`<sup>Optional</sup> <a name="writtenDataBytes" id="@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes"></a>

```java
public java.lang.Number getWrittenDataBytes();
```

- *Type:* java.lang.Number

Total amount of data written to all of a project's branches.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#written_data_bytes Project#written_data_bytes}

---

## Classes <a name="Classes" id="Classes"></a>

### ProjectBranchOutputReference <a name="ProjectBranchOutputReference" id="@cdktf/provider-neon.project.ProjectBranchOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.ProjectBranchOutputReference;

new ProjectBranchOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetDatabaseName` <a name="resetDatabaseName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetDatabaseName"></a>

```java
public void resetDatabaseName()
```

##### `resetName` <a name="resetName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetName"></a>

```java
public void resetName()
```

##### `resetRoleName` <a name="resetRoleName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetRoleName"></a>

```java
public void resetRoleName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput">databaseNameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput">roleNameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName">databaseName</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName">roleName</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `databaseNameInput`<sup>Optional</sup> <a name="databaseNameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput"></a>

```java
public java.lang.String getDatabaseNameInput();
```

- *Type:* java.lang.String

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `roleNameInput`<sup>Optional</sup> <a name="roleNameInput" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput"></a>

```java
public java.lang.String getRoleNameInput();
```

- *Type:* java.lang.String

---

##### `databaseName`<sup>Required</sup> <a name="databaseName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName"></a>

```java
public java.lang.String getDatabaseName();
```

- *Type:* java.lang.String

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `roleName`<sup>Required</sup> <a name="roleName" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName"></a>

```java
public java.lang.String getRoleName();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue"></a>

```java
public ProjectBranch getInternalValue();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---


### ProjectDefaultEndpointSettingsOutputReference <a name="ProjectDefaultEndpointSettingsOutputReference" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.ProjectDefaultEndpointSettingsOutputReference;

new ProjectDefaultEndpointSettingsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetAutoscalingLimitMaxCu` <a name="resetAutoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMaxCu"></a>

```java
public void resetAutoscalingLimitMaxCu()
```

##### `resetAutoscalingLimitMinCu` <a name="resetAutoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMinCu"></a>

```java
public void resetAutoscalingLimitMinCu()
```

##### `resetSuspendTimeoutSeconds` <a name="resetSuspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetSuspendTimeoutSeconds"></a>

```java
public void resetSuspendTimeoutSeconds()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput">autoscalingLimitMaxCuInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput">autoscalingLimitMinCuInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput">suspendTimeoutSecondsInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu">autoscalingLimitMaxCu</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu">autoscalingLimitMinCu</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds">suspendTimeoutSeconds</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `autoscalingLimitMaxCuInput`<sup>Optional</sup> <a name="autoscalingLimitMaxCuInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput"></a>

```java
public java.lang.Number getAutoscalingLimitMaxCuInput();
```

- *Type:* java.lang.Number

---

##### `autoscalingLimitMinCuInput`<sup>Optional</sup> <a name="autoscalingLimitMinCuInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput"></a>

```java
public java.lang.Number getAutoscalingLimitMinCuInput();
```

- *Type:* java.lang.Number

---

##### `suspendTimeoutSecondsInput`<sup>Optional</sup> <a name="suspendTimeoutSecondsInput" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput"></a>

```java
public java.lang.Number getSuspendTimeoutSecondsInput();
```

- *Type:* java.lang.Number

---

##### `autoscalingLimitMaxCu`<sup>Required</sup> <a name="autoscalingLimitMaxCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu"></a>

```java
public java.lang.Number getAutoscalingLimitMaxCu();
```

- *Type:* java.lang.Number

---

##### `autoscalingLimitMinCu`<sup>Required</sup> <a name="autoscalingLimitMinCu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu"></a>

```java
public java.lang.Number getAutoscalingLimitMinCu();
```

- *Type:* java.lang.Number

---

##### `suspendTimeoutSeconds`<sup>Required</sup> <a name="suspendTimeoutSeconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds"></a>

```java
public java.lang.Number getSuspendTimeoutSeconds();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue"></a>

```java
public ProjectDefaultEndpointSettings getInternalValue();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---


### ProjectQuotaOutputReference <a name="ProjectQuotaOutputReference" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.neon.project.ProjectQuotaOutputReference;

new ProjectQuotaOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetActiveTimeSeconds` <a name="resetActiveTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetActiveTimeSeconds"></a>

```java
public void resetActiveTimeSeconds()
```

##### `resetComputeTimeSeconds` <a name="resetComputeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetComputeTimeSeconds"></a>

```java
public void resetComputeTimeSeconds()
```

##### `resetDataTransferBytes` <a name="resetDataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetDataTransferBytes"></a>

```java
public void resetDataTransferBytes()
```

##### `resetLogicalSizeBytes` <a name="resetLogicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetLogicalSizeBytes"></a>

```java
public void resetLogicalSizeBytes()
```

##### `resetWrittenDataBytes` <a name="resetWrittenDataBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetWrittenDataBytes"></a>

```java
public void resetWrittenDataBytes()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput">activeTimeSecondsInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput">computeTimeSecondsInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput">dataTransferBytesInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput">logicalSizeBytesInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput">writtenDataBytesInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds">activeTimeSeconds</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds">computeTimeSeconds</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes">dataTransferBytes</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes">logicalSizeBytes</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes">writtenDataBytes</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `activeTimeSecondsInput`<sup>Optional</sup> <a name="activeTimeSecondsInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput"></a>

```java
public java.lang.Number getActiveTimeSecondsInput();
```

- *Type:* java.lang.Number

---

##### `computeTimeSecondsInput`<sup>Optional</sup> <a name="computeTimeSecondsInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput"></a>

```java
public java.lang.Number getComputeTimeSecondsInput();
```

- *Type:* java.lang.Number

---

##### `dataTransferBytesInput`<sup>Optional</sup> <a name="dataTransferBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput"></a>

```java
public java.lang.Number getDataTransferBytesInput();
```

- *Type:* java.lang.Number

---

##### `logicalSizeBytesInput`<sup>Optional</sup> <a name="logicalSizeBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput"></a>

```java
public java.lang.Number getLogicalSizeBytesInput();
```

- *Type:* java.lang.Number

---

##### `writtenDataBytesInput`<sup>Optional</sup> <a name="writtenDataBytesInput" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput"></a>

```java
public java.lang.Number getWrittenDataBytesInput();
```

- *Type:* java.lang.Number

---

##### `activeTimeSeconds`<sup>Required</sup> <a name="activeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds"></a>

```java
public java.lang.Number getActiveTimeSeconds();
```

- *Type:* java.lang.Number

---

##### `computeTimeSeconds`<sup>Required</sup> <a name="computeTimeSeconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds"></a>

```java
public java.lang.Number getComputeTimeSeconds();
```

- *Type:* java.lang.Number

---

##### `dataTransferBytes`<sup>Required</sup> <a name="dataTransferBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes"></a>

```java
public java.lang.Number getDataTransferBytes();
```

- *Type:* java.lang.Number

---

##### `logicalSizeBytes`<sup>Required</sup> <a name="logicalSizeBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes"></a>

```java
public java.lang.Number getLogicalSizeBytes();
```

- *Type:* java.lang.Number

---

##### `writtenDataBytes`<sup>Required</sup> <a name="writtenDataBytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes"></a>

```java
public java.lang.Number getWrittenDataBytes();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue"></a>

```java
public ProjectQuota getInternalValue();
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---



