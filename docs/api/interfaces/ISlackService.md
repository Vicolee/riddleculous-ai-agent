[@elizaos/core v0.1.8+build.1](../index.md) / ISlackService

# Interface: ISlackService

## Extends

- [`Service`](../classes/Service.md)

## Properties

### client

> **client**: `any`

#### Defined in

[packages/core/src/types.ts:1477](https://github.com/Vicolee/riddleculous-ai-agent/blob/main/packages/core/src/types.ts#L1477)

## Accessors

### serviceType

#### Get Signature

> **get** **serviceType**(): [`ServiceType`](../enumerations/ServiceType.md)

##### Returns

[`ServiceType`](../enumerations/ServiceType.md)

#### Inherited from

[`Service`](../classes/Service.md).[`serviceType`](../classes/Service.md#serviceType-1)

#### Defined in

[packages/core/src/types.ts:1169](https://github.com/Vicolee/riddleculous-ai-agent/blob/main/packages/core/src/types.ts#L1169)

## Methods

### initialize()

> `abstract` **initialize**(`runtime`): `Promise`\<`void`\>

Add abstract initialize method that must be implemented by derived classes

#### Parameters

• **runtime**: [`IAgentRuntime`](IAgentRuntime.md)

#### Returns

`Promise`\<`void`\>

#### Inherited from

[`Service`](../classes/Service.md).[`initialize`](../classes/Service.md#initialize)

#### Defined in

[packages/core/src/types.ts:1174](https://github.com/Vicolee/riddleculous-ai-agent/blob/main/packages/core/src/types.ts#L1174)
