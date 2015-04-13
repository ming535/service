# convox/service

Create a CloudFormation stack for a Convox service.

## Usage

    $ docker run convox/service redis

## Parameters

Different services will expect different parameters:

#### Redis

| Name                | Description                                                                |
|---------------------|----------------------------------------------------------------------------|
| `AllowSSHFrom`      | Allow SSH from this CIDR block                                             |
| `AvailabilityZones` | A comma-delimited list of availability zones to use (specify 3)            |
| `Password`          | Server password                                                            |

## License

Apache 2.0 &copy; 2015 Convox, Inc.