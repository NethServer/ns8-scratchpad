# TCP service endpoint Schema

```txt
http://schema.nethserver.org/cluster/alter-external-domain-input.json#/$defs/tcp-service-endpoint
```

Initial TCP backend endpoint configuration

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                            |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [alter-external-domain-input.json\*](cluster/alter-external-domain-input.json "open original schema") |

## tcp-service-endpoint Type

`object` ([TCP service endpoint](alter-external-domain-input-defs-tcp-service-endpoint.md))

# tcp-service-endpoint Properties

| Property      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                  |
| :------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [host](#host) | Merged    | Required | cannot be null | [alter-external-domain input](alter-external-domain-input-defs-tcp-service-endpoint-properties-host.md "http://schema.nethserver.org/cluster/alter-external-domain-input.json#/$defs/tcp-service-endpoint/properties/host") |
| [port](#port) | `integer` | Required | cannot be null | [alter-external-domain input](alter-external-domain-input-defs-tcp-service-endpoint-properties-port.md "http://schema.nethserver.org/cluster/alter-external-domain-input.json#/$defs/tcp-service-endpoint/properties/port") |

## host



`host`

* is required

* Type: `string` ([Details](alter-external-domain-input-defs-tcp-service-endpoint-properties-host.md))

* cannot be null

* defined in: [alter-external-domain input](alter-external-domain-input-defs-tcp-service-endpoint-properties-host.md "http://schema.nethserver.org/cluster/alter-external-domain-input.json#/$defs/tcp-service-endpoint/properties/host")

### host Type

`string` ([Details](alter-external-domain-input-defs-tcp-service-endpoint-properties-host.md))

one (and only one) of

* [Untitled undefined type in alter-external-domain input](alter-external-domain-input-defs-tcp-service-endpoint-properties-host-oneof-0.md "check type definition")

* [Untitled undefined type in alter-external-domain input](alter-external-domain-input-defs-tcp-service-endpoint-properties-host-oneof-1.md "check type definition")

## port



`port`

* is required

* Type: `integer`

* cannot be null

* defined in: [alter-external-domain input](alter-external-domain-input-defs-tcp-service-endpoint-properties-port.md "http://schema.nethserver.org/cluster/alter-external-domain-input.json#/$defs/tcp-service-endpoint/properties/port")

### port Type

`integer`

### port Constraints

**maximum**: the value of this number must smaller than or equal to: `65535`

**minimum**: the value of this number must greater than or equal to: `1`
