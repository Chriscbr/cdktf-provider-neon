# `neon_endpoint`

Refer to the Terraform Registory for docs: [`neon_endpoint`](https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint).

# `endpoint` Submodule <a name="`endpoint` Submodule" id="@cdktf/provider-neon.endpoint"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Endpoint <a name="Endpoint" id="@cdktf/provider-neon.endpoint.Endpoint"></a>

Represents a {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint neon_endpoint}.

#### Initializers <a name="Initializers" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import endpoint

endpoint.Endpoint(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  branch_id: str,
  project_id: str,
  autoscaling_limit_max_cu: typing.Union[int, float] = None,
  autoscaling_limit_min_cu: typing.Union[int, float] = None,
  compute_provisioner: str = None,
  disabled: typing.Union[bool, IResolvable] = None,
  pg_settings: typing.Mapping[str] = None,
  pooler_enabled: typing.Union[bool, IResolvable] = None,
  pooler_mode: str = None,
  region_id: str = None,
  suspend_timeout_seconds: typing.Union[int, float] = None,
  type: str = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.branchId">branch_id</a></code> | <code>str</code> | Branch ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.projectId">project_id</a></code> | <code>str</code> | Project ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.autoscalingLimitMaxCu">autoscaling_limit_max_cu</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.autoscalingLimitMinCu">autoscaling_limit_min_cu</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.computeProvisioner">compute_provisioner</a></code> | <code>str</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.disabled">disabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Disable the endpoint. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.pgSettings">pg_settings</a></code> | <code>typing.Mapping[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.poolerEnabled">pooler_enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.poolerMode">pooler_mode</a></code> | <code>str</code> | Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.regionId">region_id</a></code> | <code>str</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.suspendTimeoutSeconds">suspend_timeout_seconds</a></code> | <code>typing.Union[int, float]</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.type">type</a></code> | <code>str</code> | Access type. **Note** that "read_write" is the only supported type yet. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `branch_id`<sup>Required</sup> <a name="branch_id" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.branchId"></a>

- *Type:* str

Branch ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#branch_id Endpoint#branch_id}

---

##### `project_id`<sup>Required</sup> <a name="project_id" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.projectId"></a>

- *Type:* str

Project ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#project_id Endpoint#project_id}

---

##### `autoscaling_limit_max_cu`<sup>Optional</sup> <a name="autoscaling_limit_max_cu" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.autoscalingLimitMaxCu"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}.

---

##### `autoscaling_limit_min_cu`<sup>Optional</sup> <a name="autoscaling_limit_min_cu" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.autoscalingLimitMinCu"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}.

---

##### `compute_provisioner`<sup>Optional</sup> <a name="compute_provisioner" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.computeProvisioner"></a>

- *Type:* str

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#compute_provisioner Endpoint#compute_provisioner}

---

##### `disabled`<sup>Optional</sup> <a name="disabled" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.disabled"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Disable the endpoint.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#disabled Endpoint#disabled}

---

##### `pg_settings`<sup>Optional</sup> <a name="pg_settings" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.pgSettings"></a>

- *Type:* typing.Mapping[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}.

---

##### `pooler_enabled`<sup>Optional</sup> <a name="pooler_enabled" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.poolerEnabled"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_enabled Endpoint#pooler_enabled}

---

##### `pooler_mode`<sup>Optional</sup> <a name="pooler_mode" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.poolerMode"></a>

- *Type:* str

Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_mode Endpoint#pooler_mode}

---

##### `region_id`<sup>Optional</sup> <a name="region_id" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.regionId"></a>

- *Type:* str

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#region_id Endpoint#region_id}

---

##### `suspend_timeout_seconds`<sup>Optional</sup> <a name="suspend_timeout_seconds" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.suspendTimeoutSeconds"></a>

- *Type:* typing.Union[int, float]

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#suspend_timeout_seconds Endpoint#suspend_timeout_seconds}

---

##### `type`<sup>Optional</sup> <a name="type" id="@cdktf/provider-neon.endpoint.Endpoint.Initializer.parameter.type"></a>

- *Type:* str

Access type. **Note** that "read_write" is the only supported type yet.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#type Endpoint#type}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget">add_move_target</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.importFrom">import_from</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.moveTo">move_to</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMaxCu">reset_autoscaling_limit_max_cu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMinCu">reset_autoscaling_limit_min_cu</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetComputeProvisioner">reset_compute_provisioner</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetDisabled">reset_disabled</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetPgSettings">reset_pg_settings</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetPoolerEnabled">reset_pooler_enabled</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetPoolerMode">reset_pooler_mode</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetRegionId">reset_region_id</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetSuspendTimeoutSeconds">reset_suspend_timeout_seconds</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.resetType">reset_type</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktf/provider-neon.endpoint.Endpoint.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktf/provider-neon.endpoint.Endpoint.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktf/provider-neon.endpoint.Endpoint.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktf/provider-neon.endpoint.Endpoint.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="@cdktf/provider-neon.endpoint.Endpoint.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktf/provider-neon.endpoint.Endpoint.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `add_move_target` <a name="add_move_target" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget"></a>

```python
def add_move_target(
  move_target: str
) -> None
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktf/provider-neon.endpoint.Endpoint.addMoveTarget.parameter.moveTarget"></a>

- *Type:* str

The string move target that will correspond to this resource.

---

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `import_from` <a name="import_from" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom"></a>

```python
def import_from(
  id: str,
  provider: TerraformProvider = None
) -> None
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.id"></a>

- *Type:* str

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.importFrom.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktf/provider-neon.endpoint.Endpoint.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `move_to` <a name="move_to" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo"></a>

```python
def move_to(
  move_target: str,
  index: typing.Union[str, typing.Union[int, float]] = None
) -> None
```

Moves this resource to the target resource given by moveTarget.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.moveTarget"></a>

- *Type:* str

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktf/provider-neon.endpoint.Endpoint.moveTo.parameter.index"></a>

- *Type:* typing.Union[str, typing.Union[int, float]]

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `reset_autoscaling_limit_max_cu` <a name="reset_autoscaling_limit_max_cu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMaxCu"></a>

```python
def reset_autoscaling_limit_max_cu() -> None
```

##### `reset_autoscaling_limit_min_cu` <a name="reset_autoscaling_limit_min_cu" id="@cdktf/provider-neon.endpoint.Endpoint.resetAutoscalingLimitMinCu"></a>

```python
def reset_autoscaling_limit_min_cu() -> None
```

##### `reset_compute_provisioner` <a name="reset_compute_provisioner" id="@cdktf/provider-neon.endpoint.Endpoint.resetComputeProvisioner"></a>

```python
def reset_compute_provisioner() -> None
```

##### `reset_disabled` <a name="reset_disabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetDisabled"></a>

```python
def reset_disabled() -> None
```

##### `reset_pg_settings` <a name="reset_pg_settings" id="@cdktf/provider-neon.endpoint.Endpoint.resetPgSettings"></a>

```python
def reset_pg_settings() -> None
```

##### `reset_pooler_enabled` <a name="reset_pooler_enabled" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerEnabled"></a>

```python
def reset_pooler_enabled() -> None
```

##### `reset_pooler_mode` <a name="reset_pooler_mode" id="@cdktf/provider-neon.endpoint.Endpoint.resetPoolerMode"></a>

```python
def reset_pooler_mode() -> None
```

##### `reset_region_id` <a name="reset_region_id" id="@cdktf/provider-neon.endpoint.Endpoint.resetRegionId"></a>

```python
def reset_region_id() -> None
```

##### `reset_suspend_timeout_seconds` <a name="reset_suspend_timeout_seconds" id="@cdktf/provider-neon.endpoint.Endpoint.resetSuspendTimeoutSeconds"></a>

```python
def reset_suspend_timeout_seconds() -> None
```

##### `reset_type` <a name="reset_type" id="@cdktf/provider-neon.endpoint.Endpoint.resetType"></a>

```python
def reset_type() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource">is_terraform_resource</a></code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport">generate_config_for_import</a></code> | Generates CDKTF code for importing a Endpoint resource upon running "cdktf plan <stack-name>". |

---

##### `is_construct` <a name="is_construct" id="@cdktf/provider-neon.endpoint.Endpoint.isConstruct"></a>

```python
from cdktf_cdktf_provider_neon import endpoint

endpoint.Endpoint.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement"></a>

```python
from cdktf_cdktf_provider_neon import endpoint

endpoint.Endpoint.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource"></a>

```python
from cdktf_cdktf_provider_neon import endpoint

endpoint.Endpoint.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktf/provider-neon.endpoint.Endpoint.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

##### `generate_config_for_import` <a name="generate_config_for_import" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport"></a>

```python
from cdktf_cdktf_provider_neon import endpoint

endpoint.Endpoint.generate_config_for_import(
  scope: Construct,
  import_to_id: str,
  import_from_id: str,
  provider: TerraformProvider = None
)
```

Generates CDKTF code for importing a Endpoint resource upon running "cdktf plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `import_to_id`<sup>Required</sup> <a name="import_to_id" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importToId"></a>

- *Type:* str

The construct id used in the generated config for the Endpoint to import.

---

###### `import_from_id`<sup>Required</sup> <a name="import_from_id" id="@cdktf/provider-neon.endpoint.Endpoint.generateConfigForImport.parameter.importFromId"></a>

- *Type:* str

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
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.host">host</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost">proxy_host</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput">autoscaling_limit_max_cu_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput">autoscaling_limit_min_cu_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput">branch_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput">compute_provisioner_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput">disabled_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput">pg_settings_input</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput">pooler_enabled_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput">pooler_mode_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput">project_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput">region_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput">suspend_timeout_seconds_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu">autoscaling_limit_max_cu</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu">autoscaling_limit_min_cu</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.branchId">branch_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner">compute_provisioner</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.disabled">disabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings">pg_settings</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled">pooler_enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode">pooler_mode</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.projectId">project_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.regionId">region_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds">suspend_timeout_seconds</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.type">type</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktf/provider-neon.endpoint.Endpoint.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktf/provider-neon.endpoint.Endpoint.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktf/provider-neon.endpoint.Endpoint.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktf/provider-neon.endpoint.Endpoint.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktf/provider-neon.endpoint.Endpoint.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.endpoint.Endpoint.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.endpoint.Endpoint.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-neon.endpoint.Endpoint.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-neon.endpoint.Endpoint.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.endpoint.Endpoint.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.Endpoint.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.endpoint.Endpoint.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `host`<sup>Required</sup> <a name="host" id="@cdktf/provider-neon.endpoint.Endpoint.property.host"></a>

```python
host: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktf/provider-neon.endpoint.Endpoint.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `proxy_host`<sup>Required</sup> <a name="proxy_host" id="@cdktf/provider-neon.endpoint.Endpoint.property.proxyHost"></a>

```python
proxy_host: str
```

- *Type:* str

---

##### `autoscaling_limit_max_cu_input`<sup>Optional</sup> <a name="autoscaling_limit_max_cu_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCuInput"></a>

```python
autoscaling_limit_max_cu_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `autoscaling_limit_min_cu_input`<sup>Optional</sup> <a name="autoscaling_limit_min_cu_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCuInput"></a>

```python
autoscaling_limit_min_cu_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `branch_id_input`<sup>Optional</sup> <a name="branch_id_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchIdInput"></a>

```python
branch_id_input: str
```

- *Type:* str

---

##### `compute_provisioner_input`<sup>Optional</sup> <a name="compute_provisioner_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisionerInput"></a>

```python
compute_provisioner_input: str
```

- *Type:* str

---

##### `disabled_input`<sup>Optional</sup> <a name="disabled_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabledInput"></a>

```python
disabled_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `pg_settings_input`<sup>Optional</sup> <a name="pg_settings_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettingsInput"></a>

```python
pg_settings_input: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `pooler_enabled_input`<sup>Optional</sup> <a name="pooler_enabled_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabledInput"></a>

```python
pooler_enabled_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `pooler_mode_input`<sup>Optional</sup> <a name="pooler_mode_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerModeInput"></a>

```python
pooler_mode_input: str
```

- *Type:* str

---

##### `project_id_input`<sup>Optional</sup> <a name="project_id_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectIdInput"></a>

```python
project_id_input: str
```

- *Type:* str

---

##### `region_id_input`<sup>Optional</sup> <a name="region_id_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionIdInput"></a>

```python
region_id_input: str
```

- *Type:* str

---

##### `suspend_timeout_seconds_input`<sup>Optional</sup> <a name="suspend_timeout_seconds_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSecondsInput"></a>

```python
suspend_timeout_seconds_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="@cdktf/provider-neon.endpoint.Endpoint.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `autoscaling_limit_max_cu`<sup>Required</sup> <a name="autoscaling_limit_max_cu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMaxCu"></a>

```python
autoscaling_limit_max_cu: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `autoscaling_limit_min_cu`<sup>Required</sup> <a name="autoscaling_limit_min_cu" id="@cdktf/provider-neon.endpoint.Endpoint.property.autoscalingLimitMinCu"></a>

```python
autoscaling_limit_min_cu: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `branch_id`<sup>Required</sup> <a name="branch_id" id="@cdktf/provider-neon.endpoint.Endpoint.property.branchId"></a>

```python
branch_id: str
```

- *Type:* str

---

##### `compute_provisioner`<sup>Required</sup> <a name="compute_provisioner" id="@cdktf/provider-neon.endpoint.Endpoint.property.computeProvisioner"></a>

```python
compute_provisioner: str
```

- *Type:* str

---

##### `disabled`<sup>Required</sup> <a name="disabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.disabled"></a>

```python
disabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `pg_settings`<sup>Required</sup> <a name="pg_settings" id="@cdktf/provider-neon.endpoint.Endpoint.property.pgSettings"></a>

```python
pg_settings: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `pooler_enabled`<sup>Required</sup> <a name="pooler_enabled" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerEnabled"></a>

```python
pooler_enabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `pooler_mode`<sup>Required</sup> <a name="pooler_mode" id="@cdktf/provider-neon.endpoint.Endpoint.property.poolerMode"></a>

```python
pooler_mode: str
```

- *Type:* str

---

##### `project_id`<sup>Required</sup> <a name="project_id" id="@cdktf/provider-neon.endpoint.Endpoint.property.projectId"></a>

```python
project_id: str
```

- *Type:* str

---

##### `region_id`<sup>Required</sup> <a name="region_id" id="@cdktf/provider-neon.endpoint.Endpoint.property.regionId"></a>

```python
region_id: str
```

- *Type:* str

---

##### `suspend_timeout_seconds`<sup>Required</sup> <a name="suspend_timeout_seconds" id="@cdktf/provider-neon.endpoint.Endpoint.property.suspendTimeoutSeconds"></a>

```python
suspend_timeout_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type`<sup>Required</sup> <a name="type" id="@cdktf/provider-neon.endpoint.Endpoint.property.type"></a>

```python
type: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktf/provider-neon.endpoint.Endpoint.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### EndpointConfig <a name="EndpointConfig" id="@cdktf/provider-neon.endpoint.EndpointConfig"></a>

#### Initializer <a name="Initializer" id="@cdktf/provider-neon.endpoint.EndpointConfig.Initializer"></a>

```python
from cdktf_cdktf_provider_neon import endpoint

endpoint.EndpointConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  branch_id: str,
  project_id: str,
  autoscaling_limit_max_cu: typing.Union[int, float] = None,
  autoscaling_limit_min_cu: typing.Union[int, float] = None,
  compute_provisioner: str = None,
  disabled: typing.Union[bool, IResolvable] = None,
  pg_settings: typing.Mapping[str] = None,
  pooler_enabled: typing.Union[bool, IResolvable] = None,
  pooler_mode: str = None,
  region_id: str = None,
  suspend_timeout_seconds: typing.Union[int, float] = None,
  type: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId">branch_id</a></code> | <code>str</code> | Branch ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId">project_id</a></code> | <code>str</code> | Project ID. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu">autoscaling_limit_max_cu</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu">autoscaling_limit_min_cu</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner">compute_provisioner</a></code> | <code>str</code> | Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled">disabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Disable the endpoint. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings">pg_settings</a></code> | <code>typing.Mapping[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled">pooler_enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode">pooler_mode</a></code> | <code>str</code> | Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId">region_id</a></code> | <code>str</code> | AWS Region. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds">suspend_timeout_seconds</a></code> | <code>typing.Union[int, float]</code> | Duration of inactivity in seconds after which the compute endpoint is automatically suspended. |
| <code><a href="#@cdktf/provider-neon.endpoint.EndpointConfig.property.type">type</a></code> | <code>str</code> | Access type. **Note** that "read_write" is the only supported type yet. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `branch_id`<sup>Required</sup> <a name="branch_id" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.branchId"></a>

```python
branch_id: str
```

- *Type:* str

Branch ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#branch_id Endpoint#branch_id}

---

##### `project_id`<sup>Required</sup> <a name="project_id" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.projectId"></a>

```python
project_id: str
```

- *Type:* str

Project ID.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#project_id Endpoint#project_id}

---

##### `autoscaling_limit_max_cu`<sup>Optional</sup> <a name="autoscaling_limit_max_cu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMaxCu"></a>

```python
autoscaling_limit_max_cu: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_max_cu Endpoint#autoscaling_limit_max_cu}.

---

##### `autoscaling_limit_min_cu`<sup>Optional</sup> <a name="autoscaling_limit_min_cu" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.autoscalingLimitMinCu"></a>

```python
autoscaling_limit_min_cu: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#autoscaling_limit_min_cu Endpoint#autoscaling_limit_min_cu}.

---

##### `compute_provisioner`<sup>Optional</sup> <a name="compute_provisioner" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.computeProvisioner"></a>

```python
compute_provisioner: str
```

- *Type:* str

Provisioner The Neon compute provisioner. Specify the k8s-neonvm provisioner to create a compute endpoint that supports Autoscaling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#compute_provisioner Endpoint#compute_provisioner}

---

##### `disabled`<sup>Optional</sup> <a name="disabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.disabled"></a>

```python
disabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Disable the endpoint.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#disabled Endpoint#disabled}

---

##### `pg_settings`<sup>Optional</sup> <a name="pg_settings" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.pgSettings"></a>

```python
pg_settings: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pg_settings Endpoint#pg_settings}.

---

##### `pooler_enabled`<sup>Optional</sup> <a name="pooler_enabled" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerEnabled"></a>

```python
pooler_enabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Activate connection pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_enabled Endpoint#pooler_enabled}

---

##### `pooler_mode`<sup>Optional</sup> <a name="pooler_mode" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.poolerMode"></a>

```python
pooler_mode: str
```

- *Type:* str

Mode of connections pooling. See details: https://neon.tech/docs/connect/connection-pooling.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#pooler_mode Endpoint#pooler_mode}

---

##### `region_id`<sup>Optional</sup> <a name="region_id" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.regionId"></a>

```python
region_id: str
```

- *Type:* str

AWS Region.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#region_id Endpoint#region_id}

---

##### `suspend_timeout_seconds`<sup>Optional</sup> <a name="suspend_timeout_seconds" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.suspendTimeoutSeconds"></a>

```python
suspend_timeout_seconds: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Duration of inactivity in seconds after which the compute endpoint is automatically suspended.

The value 0 means use the global default.
The value -1 means never suspend. The default value is 300 seconds (5 minutes).
The maximum value is 604800 seconds (1 week)

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#suspend_timeout_seconds Endpoint#suspend_timeout_seconds}

---

##### `type`<sup>Optional</sup> <a name="type" id="@cdktf/provider-neon.endpoint.EndpointConfig.property.type"></a>

```python
type: str
```

- *Type:* str

Access type. **Note** that "read_write" is the only supported type yet.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kislerdm/neon/0.2.5/docs/resources/endpoint#type Endpoint#type}

---



