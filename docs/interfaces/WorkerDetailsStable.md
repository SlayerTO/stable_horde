[@zeldafan0225/stable_horde](../README.md) / [Exports](../modules.md) / WorkerDetailsStable

# Interface: WorkerDetailsStable

## Hierarchy

- [`WorkerDetails`](WorkerDetails.md)

  ↳ **`WorkerDetailsStable`**

## Table of contents

### Properties

- [bridge\_agent](WorkerDetailsStable.md#bridge_agent)
- [contact](WorkerDetailsStable.md#contact)
- [id](WorkerDetailsStable.md#id)
- [img2img](WorkerDetailsStable.md#img2img)
- [info](WorkerDetailsStable.md#info)
- [kudos\_details](WorkerDetailsStable.md#kudos_details)
- [kudos\_rewards](WorkerDetailsStable.md#kudos_rewards)
- [maintenance\_mode](WorkerDetailsStable.md#maintenance_mode)
- [max\_pixels](WorkerDetailsStable.md#max_pixels)
- [megapixelsteps\_generated](WorkerDetailsStable.md#megapixelsteps_generated)
- [models](WorkerDetailsStable.md#models)
- [name](WorkerDetailsStable.md#name)
- [nsfw](WorkerDetailsStable.md#nsfw)
- [online](WorkerDetailsStable.md#online)
- [owner](WorkerDetailsStable.md#owner)
- [painting](WorkerDetailsStable.md#painting)
- [paused](WorkerDetailsStable.md#paused)
- [performance](WorkerDetailsStable.md#performance)
- [post-processing](WorkerDetailsStable.md#post-processing)
- [requests\_fulfilled](WorkerDetailsStable.md#requests_fulfilled)
- [suspicious](WorkerDetailsStable.md#suspicious)
- [team](WorkerDetailsStable.md#team)
- [threads](WorkerDetailsStable.md#threads)
- [trusted](WorkerDetailsStable.md#trusted)
- [uncompleted\_jobs](WorkerDetailsStable.md#uncompleted_jobs)
- [uptime](WorkerDetailsStable.md#uptime)

## Properties

### bridge\_agent

• `Optional` **bridge\_agent**: `string`

The bridge agent name, version and website
@default: unknown:0:unknown
@example: AI Horde Worker:11:https://github.com/db0/AI-Horde-Worker
@maxLength: 1000

#### Inherited from

[WorkerDetails](WorkerDetails.md).[bridge_agent](WorkerDetails.md#bridge_agent)

#### Defined in

[index.ts:2610](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2610)

___

### contact

• `Optional` **contact**: `string`

(Privileged) Contact details for the horde admins to reach the owner of this worker in emergencies.

**`Example`**

```ts
email@example.com
```

**`Min Length`**

5

**`Max Length`**

500

#### Inherited from

[WorkerDetails](WorkerDetails.md).[contact](WorkerDetails.md#contact)

#### Defined in

[index.ts:2603](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2603)

___

### id

• `Optional` **id**: `string`

The UUID of this worker.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[id](WorkerDetails.md#id)

#### Defined in

[index.ts:2617](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2617)

___

### img2img

• `Optional` **img2img**: `boolean`

If True, this worker supports and allows img2img requests.

#### Defined in

[index.ts:2556](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2556)

___

### info

• `Optional` **info**: `string`

Extra information or comments about this worker provided by its owner.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[info](WorkerDetails.md#info)

#### Defined in

[index.ts:2580](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2580)

___

### kudos\_details

• `Optional` **kudos\_details**: [`WorkerKudosDetails`](WorkerKudosDetails.md)

#### Inherited from

[WorkerDetails](WorkerDetails.md).[kudos_details](WorkerDetails.md#kudos_details)

#### Defined in

[index.ts:2568](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2568)

___

### kudos\_rewards

• `Optional` **kudos\_rewards**: `number`

How many Kudos this worker has been rewarded in total.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[kudos_rewards](WorkerDetails.md#kudos_rewards)

#### Defined in

[index.ts:2567](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2567)

___

### maintenance\_mode

• `Optional` **maintenance\_mode**: `boolean`

When True, this worker will not pick up any new requests

#### Inherited from

[WorkerDetails](WorkerDetails.md).[maintenance_mode](WorkerDetails.md#maintenance_mode)

#### Defined in

[index.ts:2576](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2576)

___

### max\_pixels

• `Optional` **max\_pixels**: `number`

The maximum pixels in resolution this workr can generate

#### Defined in

[index.ts:2552](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2552)

___

### megapixelsteps\_generated

• `Optional` **megapixelsteps\_generated**: `number`

How many megapixelsteps this worker has generated until now

#### Defined in

[index.ts:2554](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2554)

___

### models

• `Optional` **models**: `string`[]

Which models this worker if offerring

#### Inherited from

[WorkerDetails](WorkerDetails.md).[models](WorkerDetails.md#models)

#### Defined in

[index.ts:2595](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2595)

___

### name

• `Optional` **name**: `string`

The Name given to this worker.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[name](WorkerDetails.md#name)

#### Defined in

[index.ts:2615](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2615)

___

### nsfw

• `Optional` **nsfw**: `boolean`

Whether this worker can generate NSFW requests or not.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[nsfw](WorkerDetails.md#nsfw)

#### Defined in

[index.ts:2582](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2582)

___

### online

• `Optional` **online**: `boolean`

True if the worker has checked-in the past 5 minutes.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[online](WorkerDetails.md#online)

#### Defined in

[index.ts:2619](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2619)

___

### owner

• `Optional` **owner**: `string`

Privileged or public if the owner has allowed it. The alias of the owner of this worker.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[owner](WorkerDetails.md#owner)

#### Defined in

[index.ts:2584](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2584)

___

### painting

• `Optional` **painting**: `boolean`

If True, this worker supports and allows inpainting requests.

#### Defined in

[index.ts:2558](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2558)

___

### paused

• `Optional` **paused**: `boolean`

(Privileged) When True, this worker not be given any new requests.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[paused](WorkerDetails.md#paused)

#### Defined in

[index.ts:2578](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2578)

___

### performance

• `Optional` **performance**: `string`

The average performance of this worker in human readable form.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[performance](WorkerDetails.md#performance)

#### Defined in

[index.ts:2570](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2570)

___

### post-processing

• `Optional` **post-processing**: `boolean`

If True, this worker supports and allows post-processing requests.

#### Defined in

[index.ts:2560](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2560)

___

### requests\_fulfilled

• `Optional` **requests\_fulfilled**: `number`

How many images this worker has generated.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[requests_fulfilled](WorkerDetails.md#requests_fulfilled)

#### Defined in

[index.ts:2565](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2565)

___

### suspicious

• `Optional` **suspicious**: `number`

(Privileged) How much suspicion this worker has accumulated

#### Inherited from

[WorkerDetails](WorkerDetails.md).[suspicious](WorkerDetails.md#suspicious)

#### Defined in

[index.ts:2588](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2588)

___

### team

• `Optional` **team**: [`TeamDetailsLite`](TeamDetailsLite.md)

#### Inherited from

[WorkerDetails](WorkerDetails.md).[team](WorkerDetails.md#team)

#### Defined in

[index.ts:2596](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2596)

___

### threads

• `Optional` **threads**: `number`

How many threads this worker is running.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[threads](WorkerDetails.md#threads)

#### Defined in

[index.ts:2572](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2572)

___

### trusted

• `Optional` **trusted**: `boolean`

The worker is trusted to return valid generations.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[trusted](WorkerDetails.md#trusted)

#### Defined in

[index.ts:2586](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2586)

___

### uncompleted\_jobs

• `Optional` **uncompleted\_jobs**: `number`

How many jobs this worker has left uncompleted after it started them.

**`Example`**

```ts
0
```

#### Inherited from

[WorkerDetails](WorkerDetails.md).[uncompleted_jobs](WorkerDetails.md#uncompleted_jobs)

#### Defined in

[index.ts:2593](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2593)

___

### uptime

• `Optional` **uptime**: `number`

The amount of seconds this worker has been online for this Horde.

#### Inherited from

[WorkerDetails](WorkerDetails.md).[uptime](WorkerDetails.md#uptime)

#### Defined in

[index.ts:2574](https://github.com/ZeldaFan0225/stable_horde/blob/9241243/index.ts#L2574)
