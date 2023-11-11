# `neon_project`

Refer to the Terraform Registory for docs: [`neon_project`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project).

# `project` Submodule <a name="`project` Submodule" id="@cdktf/provider-neon.project"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Project <a name="Project" id="@cdktf/provider-neon.project.Project"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project neon_project}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.Project.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import project

project.Project(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  branch: ProjectBranch = None,
  compute_provisioner: str = None,
  default_endpoint_settings: ProjectDefaultEndpointSettings = None,
  history_retention_seconds: typing.Union[int, float] = None,
  name: str = None,
  pg_version: typing.Union[int, float] = None,
  quota: ProjectQuota = None,
  region_id: str = None,
  store_password: typing.Union[bool, IResolvable] = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.branch">branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | branch block. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.computeProvisioner">compute_provisioner</a></code> | <code>str</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.defaultEndpointSettings">default_endpoint_settings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | default_endpoint_settings block. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.historyRetentionSeconds">history_retention_seconds</a></code> | <code>typing.Union[int, float]</code> | The number of seconds to retain the point-in-time restore (PITR) backup history for this project. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.name">name</a></code> | <code>str</code> | Project name. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.pgVersion">pg_version</a></code> | <code>typing.Union[int, float]</code> | Postgres version. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.quota">quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | quota block. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.regionId">region_id</a></code> | <code>str</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.project.Project.Initializer.parameter.storePassword">store_password</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Whether or not passwords are stored for roles in the Neon project. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.project.Project.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.project.Project.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.project.Project.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-neon.project.Project.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-neon.project.Project.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.project.Project.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.project.Project.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `branch`<sup>Optional</sup> <a name="branch" id="@cdktf/provider-neon.project.Project.Initializer.parameter.branch"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

branch block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#branch Project#branch}

---

##### `compute_provisioner`<sup>Optional</sup> <a name="compute_provisioner" id="@cdktf/provider-neon.project.Project.Initializer.parameter.computeProvisioner"></a>

- *Type:* str

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_provisioner Project#compute_provisioner}

---

##### `default_endpoint_settings`<sup>Optional</sup> <a name="default_endpoint_settings" id="@cdktf/provider-neon.project.Project.Initializer.parameter.defaultEndpointSettings"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

default_endpoint_settings block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#default_endpoint_settings Project#default_endpoint_settings}

---

##### `history_retention_seconds`<sup>Optional</sup> <a name="history_retention_seconds" id="@cdktf/provider-neon.project.Project.Initializer.parameter.historyRetentionSeconds"></a>

- *Type:* typing.Union[int, float]

The number of seconds to retain the point-in-time restore (PITR) backup history for this project.

Default: 7 days, see https://neon.tech/docs/reference/glossary#point-in-time-restore.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#history_retention_seconds Project#history_retention_seconds}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktf/provider-neon.project.Project.Initializer.parameter.name"></a>

- *Type:* str

Project name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `pg_version`<sup>Optional</sup> <a name="pg_version" id="@cdktf/provider-neon.project.Project.Initializer.parameter.pgVersion"></a>

- *Type:* typing.Union[int, float]

Postgres version.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#pg_version Project#pg_version}

---

##### `quota`<sup>Optional</sup> <a name="quota" id="@cdktf/provider-neon.project.Project.Initializer.parameter.quota"></a>

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

quota block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#quota Project#quota}

---

##### `region_id`<sup>Optional</sup> <a name="region_id" id="@cdktf/provider-neon.project.Project.Initializer.parameter.regionId"></a>

- *Type:* str

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#region_id Project#region_id}

---

##### `store_password`<sup>Optional</sup> <a name="store_password" id="@cdktf/provider-neon.project.Project.Initializer.parameter.storePassword"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Whether or not passwords are stored for roles in the Neon project.

Storing passwords facilitates access to Neon features that require authorization.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#store_password Project#store_password}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-neon.project.Project.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-neon.project.Project.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-neon.project.Project.addMoveTarget">add_move_target</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktf/provider-neon.project.Project.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.importFrom">import_from</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.moveTo">move_to</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktf/provider-neon.project.Project.putBranch">put_branch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.putDefaultEndpointSettings">put_default_endpoint_settings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.putQuota">put_quota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetBranch">reset_branch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetComputeProvisioner">reset_compute_provisioner</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetDefaultEndpointSettings">reset_default_endpoint_settings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetHistoryRetentionSeconds">reset_history_retention_seconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetName">reset_name</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetPgVersion">reset_pg_version</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetQuota">reset_quota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetRegionId">reset_region_id</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.resetStorePassword">reset_store_password</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktf/provider-neon.project.Project.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="@cdktf/provider-neon.project.Project.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-neon.project.Project.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.project.Project.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktf/provider-neon.project.Project.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktf/provider-neon.project.Project.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktf/provider-neon.project.Project.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="@cdktf/provider-neon.project.Project.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktf/provider-neon.project.Project.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `add_move_target` <a name="add_move_target" id="@cdktf/provider-neon.project.Project.addMoveTarget"></a>

```python
def add_move_target(
  move_target: str
) -> None
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktf/provider-neon.project.Project.addMoveTarget.parameter.moveTarget"></a>

- *Type:* str

The string move target that will correspond to this resource.

---

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-neon.project.Project.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-neon.project.Project.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `import_from` <a name="import_from" id="@cdktf/provider-neon.project.Project.importFrom"></a>

```python
def import_from(
  id: str,
  provider: TerraformProvider = None
) -> None
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.importFrom.parameter.id"></a>

- *Type:* str

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.importFrom.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.Project.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `move_to` <a name="move_to" id="@cdktf/provider-neon.project.Project.moveTo"></a>

```python
def move_to(
  move_target: str,
  index: typing.Union[str, typing.Union[int, float]] = None
) -> None
```

Moves this resource to the target resource given by moveTarget.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktf/provider-neon.project.Project.moveTo.parameter.moveTarget"></a>

- *Type:* str

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-neon.project.Project.moveTo.parameter.index"></a>

- *Type:* typing.Union[str, typing.Union[int, float]]

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `put_branch` <a name="put_branch" id="@cdktf/provider-neon.project.Project.putBranch"></a>

```python
def put_branch(
  database_name: str = None,
  name: str = None,
  role_name: str = None
) -> None
```

###### `database_name`<sup>Optional</sup> <a name="database_name" id="@cdktf/provider-neon.project.Project.putBranch.parameter.databaseName"></a>

- *Type:* str

The database name. If not specified, the default database name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#database_name Project#database_name}

---

###### `name`<sup>Optional</sup> <a name="name" id="@cdktf/provider-neon.project.Project.putBranch.parameter.name"></a>

- *Type:* str

The branch name. If not specified, the default branch name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

###### `role_name`<sup>Optional</sup> <a name="role_name" id="@cdktf/provider-neon.project.Project.putBranch.parameter.roleName"></a>

- *Type:* str

The role name. If not specified, the default role name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#role_name Project#role_name}

---

##### `put_default_endpoint_settings` <a name="put_default_endpoint_settings" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings"></a>

```python
def put_default_endpoint_settings(
  autoscaling_limit_max_cu: typing.Union[int, float] = None,
  autoscaling_limit_min_cu: typing.Union[int, float] = None,
  suspend_timeout_seconds: typing.Union[int, float] = None
) -> None
```

###### `autoscaling_limit_max_cu`<sup>Optional</sup> <a name="autoscaling_limit_max_cu" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings.parameter.autoscalingLimitMaxCu"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}.

---

###### `autoscaling_limit_min_cu`<sup>Optional</sup> <a name="autoscaling_limit_min_cu" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings.parameter.autoscalingLimitMinCu"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}.

---

###### `suspend_timeout_seconds`<sup>Optional</sup> <a name="suspend_timeout_seconds" id="@cdktf/provider-neon.project.Project.putDefaultEndpointSettings.parameter.suspendTimeoutSeconds"></a>

- *Type:* typing.Union[int, float]

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#suspend_timeout_seconds Project#suspend_timeout_seconds}

---

##### `put_quota` <a name="put_quota" id="@cdktf/provider-neon.project.Project.putQuota"></a>

```python
def put_quota(
  active_time_seconds: typing.Union[int, float] = None,
  compute_time_seconds: typing.Union[int, float] = None,
  data_transfer_bytes: typing.Union[int, float] = None,
  logical_size_bytes: typing.Union[int, float] = None,
  written_data_bytes: typing.Union[int, float] = None
) -> None
```

###### `active_time_seconds`<sup>Optional</sup> <a name="active_time_seconds" id="@cdktf/provider-neon.project.Project.putQuota.parameter.activeTimeSeconds"></a>

- *Type:* typing.Union[int, float]

The total amount of wall-clock time allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#active_time_seconds Project#active_time_seconds}

---

###### `compute_time_seconds`<sup>Optional</sup> <a name="compute_time_seconds" id="@cdktf/provider-neon.project.Project.putQuota.parameter.computeTimeSeconds"></a>

- *Type:* typing.Union[int, float]

The total amount of CPU seconds allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_time_seconds Project#compute_time_seconds}

---

###### `data_transfer_bytes`<sup>Optional</sup> <a name="data_transfer_bytes" id="@cdktf/provider-neon.project.Project.putQuota.parameter.dataTransferBytes"></a>

- *Type:* typing.Union[int, float]

Total amount of data transferred from all of a project's branches using the proxy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#data_transfer_bytes Project#data_transfer_bytes}

---

###### `logical_size_bytes`<sup>Optional</sup> <a name="logical_size_bytes" id="@cdktf/provider-neon.project.Project.putQuota.parameter.logicalSizeBytes"></a>

- *Type:* typing.Union[int, float]

Limit on the logical size of every project's branch.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#logical_size_bytes Project#logical_size_bytes}

---

###### `written_data_bytes`<sup>Optional</sup> <a name="written_data_bytes" id="@cdktf/provider-neon.project.Project.putQuota.parameter.writtenDataBytes"></a>

- *Type:* typing.Union[int, float]

Total amount of data written to all of a project's branches.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#written_data_bytes Project#written_data_bytes}

---

##### `reset_branch` <a name="reset_branch" id="@cdktf/provider-neon.project.Project.resetBranch"></a>

```python
def reset_branch() -> None
```

##### `reset_compute_provisioner` <a name="reset_compute_provisioner" id="@cdktf/provider-neon.project.Project.resetComputeProvisioner"></a>

```python
def reset_compute_provisioner() -> None
```

##### `reset_default_endpoint_settings` <a name="reset_default_endpoint_settings" id="@cdktf/provider-neon.project.Project.resetDefaultEndpointSettings"></a>

```python
def reset_default_endpoint_settings() -> None
```

##### `reset_history_retention_seconds` <a name="reset_history_retention_seconds" id="@cdktf/provider-neon.project.Project.resetHistoryRetentionSeconds"></a>

```python
def reset_history_retention_seconds() -> None
```

##### `reset_name` <a name="reset_name" id="@cdktf/provider-neon.project.Project.resetName"></a>

```python
def reset_name() -> None
```

##### `reset_pg_version` <a name="reset_pg_version" id="@cdktf/provider-neon.project.Project.resetPgVersion"></a>

```python
def reset_pg_version() -> None
```

##### `reset_quota` <a name="reset_quota" id="@cdktf/provider-neon.project.Project.resetQuota"></a>

```python
def reset_quota() -> None
```

##### `reset_region_id` <a name="reset_region_id" id="@cdktf/provider-neon.project.Project.resetRegionId"></a>

```python
def reset_region_id() -> None
```

##### `reset_store_password` <a name="reset_store_password" id="@cdktf/provider-neon.project.Project.resetStorePassword"></a>

```python
def reset_store_password() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-neon.project.Project.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.isTerraformResource">is_terraform_resource</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.generateConfigForImport">generate_config_for_import</a></code> | Generates CDKTF code for importing a Project resource upon running "cdktf plan <stack-name>". |

---

##### `is_construct` <a name="is_construct" id="@cdktf/provider-neon.project.Project.isConstruct"></a>

```python
from cdktf_cdktf_provider_neon import project

project.Project.is_construct(
  x: typing.Any
)
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

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktf/provider-neon.project.Project.isTerraformElement"></a>

```python
from cdktf_cdktf_provider_neon import project

project.Project.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.project.Project.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="@cdktf/provider-neon.project.Project.isTerraformResource"></a>

```python
from cdktf_cdktf_provider_neon import project

project.Project.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.project.Project.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

##### `generate_config_for_import` <a name="generate_config_for_import" id="@cdktf/provider-neon.project.Project.generateConfigForImport"></a>

```python
from cdktf_cdktf_provider_neon import project

project.Project.generate_config_for_import(
  scope: Construct,
  import_to_id: str,
  import_from_id: str,
  provider: TerraformProvider = None
)
```

Generates CDKTF code for importing a Project resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `import_to_id`<sup>Required</sup> <a name="import_to_id" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importToId"></a>

- *Type:* str

The construct id used in the generated config for the Project to import.

---

###### `import_from_id`<sup>Required</sup> <a name="import_from_id" id="@cdktf/provider-neon.project.Project.generateConfigForImport.parameter.importFromId"></a>

- *Type:* str

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
| <code><a href="#@cdktf/provider-neon.project.Project.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branch">branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.connectionUri">connection_uri</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseHost">database_host</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseName">database_name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databasePassword">database_password</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.databaseUser">database_user</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultBranchId">default_branch_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettings">default_endpoint_settings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quota">quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.branchInput">branch_input</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisionerInput">compute_provisioner_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput">default_endpoint_settings_input</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput">history_retention_seconds_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersionInput">pg_version_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.quotaInput">quota_input</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionIdInput">region_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePasswordInput">store_password_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.computeProvisioner">compute_provisioner</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.historyRetentionSeconds">history_retention_seconds</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.pgVersion">pg_version</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.regionId">region_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.Project.property.storePassword">store_password</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-neon.project.Project.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktf/provider-neon.project.Project.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.Project.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktf/provider-neon.project.Project.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktf/provider-neon.project.Project.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktf/provider-neon.project.Project.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktf/provider-neon.project.Project.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.project.Project.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.project.Project.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-neon.project.Project.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-neon.project.Project.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.project.Project.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.Project.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.project.Project.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `branch`<sup>Required</sup> <a name="branch" id="@cdktf/provider-neon.project.Project.property.branch"></a>

```python
branch: ProjectBranchOutputReference
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference">ProjectBranchOutputReference</a>

---

##### `connection_uri`<sup>Required</sup> <a name="connection_uri" id="@cdktf/provider-neon.project.Project.property.connectionUri"></a>

```python
connection_uri: str
```

- *Type:* str

---

##### `database_host`<sup>Required</sup> <a name="database_host" id="@cdktf/provider-neon.project.Project.property.databaseHost"></a>

```python
database_host: str
```

- *Type:* str

---

##### `database_name`<sup>Required</sup> <a name="database_name" id="@cdktf/provider-neon.project.Project.property.databaseName"></a>

```python
database_name: str
```

- *Type:* str

---

##### `database_password`<sup>Required</sup> <a name="database_password" id="@cdktf/provider-neon.project.Project.property.databasePassword"></a>

```python
database_password: str
```

- *Type:* str

---

##### `database_user`<sup>Required</sup> <a name="database_user" id="@cdktf/provider-neon.project.Project.property.databaseUser"></a>

```python
database_user: str
```

- *Type:* str

---

##### `default_branch_id`<sup>Required</sup> <a name="default_branch_id" id="@cdktf/provider-neon.project.Project.property.defaultBranchId"></a>

```python
default_branch_id: str
```

- *Type:* str

---

##### `default_endpoint_settings`<sup>Required</sup> <a name="default_endpoint_settings" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettings"></a>

```python
default_endpoint_settings: ProjectDefaultEndpointSettingsOutputReference
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference">ProjectDefaultEndpointSettingsOutputReference</a>

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.Project.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `quota`<sup>Required</sup> <a name="quota" id="@cdktf/provider-neon.project.Project.property.quota"></a>

```python
quota: ProjectQuotaOutputReference
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference">ProjectQuotaOutputReference</a>

---

##### `branch_input`<sup>Optional</sup> <a name="branch_input" id="@cdktf/provider-neon.project.Project.property.branchInput"></a>

```python
branch_input: ProjectBranch
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---

##### `compute_provisioner_input`<sup>Optional</sup> <a name="compute_provisioner_input" id="@cdktf/provider-neon.project.Project.property.computeProvisionerInput"></a>

```python
compute_provisioner_input: str
```

- *Type:* str

---

##### `default_endpoint_settings_input`<sup>Optional</sup> <a name="default_endpoint_settings_input" id="@cdktf/provider-neon.project.Project.property.defaultEndpointSettingsInput"></a>

```python
default_endpoint_settings_input: ProjectDefaultEndpointSettings
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---

##### `history_retention_seconds_input`<sup>Optional</sup> <a name="history_retention_seconds_input" id="@cdktf/provider-neon.project.Project.property.historyRetentionSecondsInput"></a>

```python
history_retention_seconds_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="@cdktf/provider-neon.project.Project.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `pg_version_input`<sup>Optional</sup> <a name="pg_version_input" id="@cdktf/provider-neon.project.Project.property.pgVersionInput"></a>

```python
pg_version_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `quota_input`<sup>Optional</sup> <a name="quota_input" id="@cdktf/provider-neon.project.Project.property.quotaInput"></a>

```python
quota_input: ProjectQuota
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---

##### `region_id_input`<sup>Optional</sup> <a name="region_id_input" id="@cdktf/provider-neon.project.Project.property.regionIdInput"></a>

```python
region_id_input: str
```

- *Type:* str

---

##### `store_password_input`<sup>Optional</sup> <a name="store_password_input" id="@cdktf/provider-neon.project.Project.property.storePasswordInput"></a>

```python
store_password_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `compute_provisioner`<sup>Required</sup> <a name="compute_provisioner" id="@cdktf/provider-neon.project.Project.property.computeProvisioner"></a>

```python
compute_provisioner: str
```

- *Type:* str

---

##### `history_retention_seconds`<sup>Required</sup> <a name="history_retention_seconds" id="@cdktf/provider-neon.project.Project.property.historyRetentionSeconds"></a>

```python
history_retention_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktf/provider-neon.project.Project.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `pg_version`<sup>Required</sup> <a name="pg_version" id="@cdktf/provider-neon.project.Project.property.pgVersion"></a>

```python
pg_version: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `region_id`<sup>Required</sup> <a name="region_id" id="@cdktf/provider-neon.project.Project.property.regionId"></a>

```python
region_id: str
```

- *Type:* str

---

##### `store_password`<sup>Required</sup> <a name="store_password" id="@cdktf/provider-neon.project.Project.property.storePassword"></a>

```python
store_password: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.Project.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-neon.project.Project.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### ProjectBranch <a name="ProjectBranch" id="@cdktf/provider-neon.project.ProjectBranch"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectBranch.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import project

project.ProjectBranch(
  database_name: str = None,
  name: str = None,
  role_name: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.databaseName">database_name</a></code> | <code>str</code> | The database name. If not specified, the default database name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.name">name</a></code> | <code>str</code> | The branch name. If not specified, the default branch name will be used. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranch.property.roleName">role_name</a></code> | <code>str</code> | The role name. If not specified, the default role name will be used. |

---

##### `database_name`<sup>Optional</sup> <a name="database_name" id="@cdktf/provider-neon.project.ProjectBranch.property.databaseName"></a>

```python
database_name: str
```

- *Type:* str

The database name. If not specified, the default database name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#database_name Project#database_name}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktf/provider-neon.project.ProjectBranch.property.name"></a>

```python
name: str
```

- *Type:* str

The branch name. If not specified, the default branch name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `role_name`<sup>Optional</sup> <a name="role_name" id="@cdktf/provider-neon.project.ProjectBranch.property.roleName"></a>

```python
role_name: str
```

- *Type:* str

The role name. If not specified, the default role name will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#role_name Project#role_name}

---

### ProjectConfig <a name="ProjectConfig" id="@cdktf/provider-neon.project.ProjectConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectConfig.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import project

project.ProjectConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  branch: ProjectBranch = None,
  compute_provisioner: str = None,
  default_endpoint_settings: ProjectDefaultEndpointSettings = None,
  history_retention_seconds: typing.Union[int, float] = None,
  name: str = None,
  pg_version: typing.Union[int, float] = None,
  quota: ProjectQuota = None,
  region_id: str = None,
  store_password: typing.Union[bool, IResolvable] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.branch">branch</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | branch block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner">compute_provisioner</a></code> | <code>str</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings">default_endpoint_settings</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | default_endpoint_settings block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds">history_retention_seconds</a></code> | <code>typing.Union[int, float]</code> | The number of seconds to retain the point-in-time restore (PITR) backup history for this project. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.name">name</a></code> | <code>str</code> | Project name. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.pgVersion">pg_version</a></code> | <code>typing.Union[int, float]</code> | Postgres version. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.quota">quota</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | quota block. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.regionId">region_id</a></code> | <code>str</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.project.ProjectConfig.property.storePassword">store_password</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Whether or not passwords are stored for roles in the Neon project. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.project.ProjectConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.project.ProjectConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-neon.project.ProjectConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-neon.project.ProjectConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.project.ProjectConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.project.ProjectConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.project.ProjectConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `branch`<sup>Optional</sup> <a name="branch" id="@cdktf/provider-neon.project.ProjectConfig.property.branch"></a>

```python
branch: ProjectBranch
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

branch block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#branch Project#branch}

---

##### `compute_provisioner`<sup>Optional</sup> <a name="compute_provisioner" id="@cdktf/provider-neon.project.ProjectConfig.property.computeProvisioner"></a>

```python
compute_provisioner: str
```

- *Type:* str

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_provisioner Project#compute_provisioner}

---

##### `default_endpoint_settings`<sup>Optional</sup> <a name="default_endpoint_settings" id="@cdktf/provider-neon.project.ProjectConfig.property.defaultEndpointSettings"></a>

```python
default_endpoint_settings: ProjectDefaultEndpointSettings
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

default_endpoint_settings block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#default_endpoint_settings Project#default_endpoint_settings}

---

##### `history_retention_seconds`<sup>Optional</sup> <a name="history_retention_seconds" id="@cdktf/provider-neon.project.ProjectConfig.property.historyRetentionSeconds"></a>

```python
history_retention_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

The number of seconds to retain the point-in-time restore (PITR) backup history for this project.

Default: 7 days, see https://neon.tech/docs/reference/glossary#point-in-time-restore.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#history_retention_seconds Project#history_retention_seconds}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktf/provider-neon.project.ProjectConfig.property.name"></a>

```python
name: str
```

- *Type:* str

Project name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#name Project#name}

---

##### `pg_version`<sup>Optional</sup> <a name="pg_version" id="@cdktf/provider-neon.project.ProjectConfig.property.pgVersion"></a>

```python
pg_version: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Postgres version.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#pg_version Project#pg_version}

---

##### `quota`<sup>Optional</sup> <a name="quota" id="@cdktf/provider-neon.project.ProjectConfig.property.quota"></a>

```python
quota: ProjectQuota
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

quota block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#quota Project#quota}

---

##### `region_id`<sup>Optional</sup> <a name="region_id" id="@cdktf/provider-neon.project.ProjectConfig.property.regionId"></a>

```python
region_id: str
```

- *Type:* str

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#region_id Project#region_id}

---

##### `store_password`<sup>Optional</sup> <a name="store_password" id="@cdktf/provider-neon.project.ProjectConfig.property.storePassword"></a>

```python
store_password: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Whether or not passwords are stored for roles in the Neon project.

Storing passwords facilitates access to Neon features that require authorization.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#store_password Project#store_password}

---

### ProjectDefaultEndpointSettings <a name="ProjectDefaultEndpointSettings" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import project

project.ProjectDefaultEndpointSettings(
  autoscaling_limit_max_cu: typing.Union[int, float] = None,
  autoscaling_limit_min_cu: typing.Union[int, float] = None,
  suspend_timeout_seconds: typing.Union[int, float] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu">autoscaling_limit_max_cu</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu">autoscaling_limit_min_cu</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds">suspend_timeout_seconds</a></code> | <code>typing.Union[int, float]</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |

---

##### `autoscaling_limit_max_cu`<sup>Optional</sup> <a name="autoscaling_limit_max_cu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMaxCu"></a>

```python
autoscaling_limit_max_cu: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_max_cu Project#autoscaling_limit_max_cu}.

---

##### `autoscaling_limit_min_cu`<sup>Optional</sup> <a name="autoscaling_limit_min_cu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.autoscalingLimitMinCu"></a>

```python
autoscaling_limit_min_cu: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#autoscaling_limit_min_cu Project#autoscaling_limit_min_cu}.

---

##### `suspend_timeout_seconds`<sup>Optional</sup> <a name="suspend_timeout_seconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettings.property.suspendTimeoutSeconds"></a>

```python
suspend_timeout_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#suspend_timeout_seconds Project#suspend_timeout_seconds}

---

### ProjectQuota <a name="ProjectQuota" id="@cdktf/provider-neon.project.ProjectQuota"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.project.ProjectQuota.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import project

project.ProjectQuota(
  active_time_seconds: typing.Union[int, float] = None,
  compute_time_seconds: typing.Union[int, float] = None,
  data_transfer_bytes: typing.Union[int, float] = None,
  logical_size_bytes: typing.Union[int, float] = None,
  written_data_bytes: typing.Union[int, float] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds">active_time_seconds</a></code> | <code>typing.Union[int, float]</code> | The total amount of wall-clock time allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds">compute_time_seconds</a></code> | <code>typing.Union[int, float]</code> | The total amount of CPU seconds allowed to be spent by the project's compute endpoints. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes">data_transfer_bytes</a></code> | <code>typing.Union[int, float]</code> | Total amount of data transferred from all of a project's branches using the proxy. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes">logical_size_bytes</a></code> | <code>typing.Union[int, float]</code> | Limit on the logical size of every project's branch. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes">written_data_bytes</a></code> | <code>typing.Union[int, float]</code> | Total amount of data written to all of a project's branches. |

---

##### `active_time_seconds`<sup>Optional</sup> <a name="active_time_seconds" id="@cdktf/provider-neon.project.ProjectQuota.property.activeTimeSeconds"></a>

```python
active_time_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

The total amount of wall-clock time allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#active_time_seconds Project#active_time_seconds}

---

##### `compute_time_seconds`<sup>Optional</sup> <a name="compute_time_seconds" id="@cdktf/provider-neon.project.ProjectQuota.property.computeTimeSeconds"></a>

```python
compute_time_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

The total amount of CPU seconds allowed to be spent by the project's compute endpoints.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#compute_time_seconds Project#compute_time_seconds}

---

##### `data_transfer_bytes`<sup>Optional</sup> <a name="data_transfer_bytes" id="@cdktf/provider-neon.project.ProjectQuota.property.dataTransferBytes"></a>

```python
data_transfer_bytes: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Total amount of data transferred from all of a project's branches using the proxy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#data_transfer_bytes Project#data_transfer_bytes}

---

##### `logical_size_bytes`<sup>Optional</sup> <a name="logical_size_bytes" id="@cdktf/provider-neon.project.ProjectQuota.property.logicalSizeBytes"></a>

```python
logical_size_bytes: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Limit on the logical size of every project's branch.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#logical_size_bytes Project#logical_size_bytes}

---

##### `written_data_bytes`<sup>Optional</sup> <a name="written_data_bytes" id="@cdktf/provider-neon.project.ProjectQuota.property.writtenDataBytes"></a>

```python
written_data_bytes: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Total amount of data written to all of a project's branches.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/project#written_data_bytes Project#written_data_bytes}

---

## Classes <a name="Classes" id="Classes"></a>

### ProjectBranchOutputReference <a name="ProjectBranchOutputReference" id="@cdktf/provider-neon.project.ProjectBranchOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import project

project.ProjectBranchOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resetDatabaseName">reset_database_name</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resetName">reset_name</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.resetRoleName">reset_role_name</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_database_name` <a name="reset_database_name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetDatabaseName"></a>

```python
def reset_database_name() -> None
```

##### `reset_name` <a name="reset_name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetName"></a>

```python
def reset_name() -> None
```

##### `reset_role_name` <a name="reset_role_name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.resetRoleName"></a>

```python
def reset_role_name() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput">database_name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput">role_name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName">database_name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName">role_name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue">internal_value</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `database_name_input`<sup>Optional</sup> <a name="database_name_input" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseNameInput"></a>

```python
database_name_input: str
```

- *Type:* str

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `role_name_input`<sup>Optional</sup> <a name="role_name_input" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleNameInput"></a>

```python
role_name_input: str
```

- *Type:* str

---

##### `database_name`<sup>Required</sup> <a name="database_name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.databaseName"></a>

```python
database_name: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `role_name`<sup>Required</sup> <a name="role_name" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.roleName"></a>

```python
role_name: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktf/provider-neon.project.ProjectBranchOutputReference.property.internalValue"></a>

```python
internal_value: ProjectBranch
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectBranch">ProjectBranch</a>

---


### ProjectDefaultEndpointSettingsOutputReference <a name="ProjectDefaultEndpointSettingsOutputReference" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import project

project.ProjectDefaultEndpointSettingsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMaxCu">reset_autoscaling_limit_max_cu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMinCu">reset_autoscaling_limit_min_cu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetSuspendTimeoutSeconds">reset_suspend_timeout_seconds</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_autoscaling_limit_max_cu` <a name="reset_autoscaling_limit_max_cu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMaxCu"></a>

```python
def reset_autoscaling_limit_max_cu() -> None
```

##### `reset_autoscaling_limit_min_cu` <a name="reset_autoscaling_limit_min_cu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetAutoscalingLimitMinCu"></a>

```python
def reset_autoscaling_limit_min_cu() -> None
```

##### `reset_suspend_timeout_seconds` <a name="reset_suspend_timeout_seconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.resetSuspendTimeoutSeconds"></a>

```python
def reset_suspend_timeout_seconds() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput">autoscaling_limit_max_cu_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput">autoscaling_limit_min_cu_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput">suspend_timeout_seconds_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu">autoscaling_limit_max_cu</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu">autoscaling_limit_min_cu</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds">suspend_timeout_seconds</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue">internal_value</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `autoscaling_limit_max_cu_input`<sup>Optional</sup> <a name="autoscaling_limit_max_cu_input" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCuInput"></a>

```python
autoscaling_limit_max_cu_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `autoscaling_limit_min_cu_input`<sup>Optional</sup> <a name="autoscaling_limit_min_cu_input" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCuInput"></a>

```python
autoscaling_limit_min_cu_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `suspend_timeout_seconds_input`<sup>Optional</sup> <a name="suspend_timeout_seconds_input" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSecondsInput"></a>

```python
suspend_timeout_seconds_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `autoscaling_limit_max_cu`<sup>Required</sup> <a name="autoscaling_limit_max_cu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMaxCu"></a>

```python
autoscaling_limit_max_cu: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `autoscaling_limit_min_cu`<sup>Required</sup> <a name="autoscaling_limit_min_cu" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.autoscalingLimitMinCu"></a>

```python
autoscaling_limit_min_cu: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `suspend_timeout_seconds`<sup>Required</sup> <a name="suspend_timeout_seconds" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.suspendTimeoutSeconds"></a>

```python
suspend_timeout_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktf/provider-neon.project.ProjectDefaultEndpointSettingsOutputReference.property.internalValue"></a>

```python
internal_value: ProjectDefaultEndpointSettings
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectDefaultEndpointSettings">ProjectDefaultEndpointSettings</a>

---


### ProjectQuotaOutputReference <a name="ProjectQuotaOutputReference" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import project

project.ProjectQuotaOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetActiveTimeSeconds">reset_active_time_seconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetComputeTimeSeconds">reset_compute_time_seconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetDataTransferBytes">reset_data_transfer_bytes</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetLogicalSizeBytes">reset_logical_size_bytes</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetWrittenDataBytes">reset_written_data_bytes</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_active_time_seconds` <a name="reset_active_time_seconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetActiveTimeSeconds"></a>

```python
def reset_active_time_seconds() -> None
```

##### `reset_compute_time_seconds` <a name="reset_compute_time_seconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetComputeTimeSeconds"></a>

```python
def reset_compute_time_seconds() -> None
```

##### `reset_data_transfer_bytes` <a name="reset_data_transfer_bytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetDataTransferBytes"></a>

```python
def reset_data_transfer_bytes() -> None
```

##### `reset_logical_size_bytes` <a name="reset_logical_size_bytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetLogicalSizeBytes"></a>

```python
def reset_logical_size_bytes() -> None
```

##### `reset_written_data_bytes` <a name="reset_written_data_bytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.resetWrittenDataBytes"></a>

```python
def reset_written_data_bytes() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput">active_time_seconds_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput">compute_time_seconds_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput">data_transfer_bytes_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput">logical_size_bytes_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput">written_data_bytes_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds">active_time_seconds</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds">compute_time_seconds</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes">data_transfer_bytes</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes">logical_size_bytes</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes">written_data_bytes</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue">internal_value</a></code> | <code><a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `active_time_seconds_input`<sup>Optional</sup> <a name="active_time_seconds_input" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSecondsInput"></a>

```python
active_time_seconds_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `compute_time_seconds_input`<sup>Optional</sup> <a name="compute_time_seconds_input" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSecondsInput"></a>

```python
compute_time_seconds_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `data_transfer_bytes_input`<sup>Optional</sup> <a name="data_transfer_bytes_input" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytesInput"></a>

```python
data_transfer_bytes_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `logical_size_bytes_input`<sup>Optional</sup> <a name="logical_size_bytes_input" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytesInput"></a>

```python
logical_size_bytes_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `written_data_bytes_input`<sup>Optional</sup> <a name="written_data_bytes_input" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytesInput"></a>

```python
written_data_bytes_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `active_time_seconds`<sup>Required</sup> <a name="active_time_seconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.activeTimeSeconds"></a>

```python
active_time_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `compute_time_seconds`<sup>Required</sup> <a name="compute_time_seconds" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.computeTimeSeconds"></a>

```python
compute_time_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `data_transfer_bytes`<sup>Required</sup> <a name="data_transfer_bytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.dataTransferBytes"></a>

```python
data_transfer_bytes: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `logical_size_bytes`<sup>Required</sup> <a name="logical_size_bytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.logicalSizeBytes"></a>

```python
logical_size_bytes: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `written_data_bytes`<sup>Required</sup> <a name="written_data_bytes" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.writtenDataBytes"></a>

```python
written_data_bytes: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktf/provider-neon.project.ProjectQuotaOutputReference.property.internalValue"></a>

```python
internal_value: ProjectQuota
```

- *Type:* <a href="#@cdktf/provider-neon.project.ProjectQuota">ProjectQuota</a>

---



