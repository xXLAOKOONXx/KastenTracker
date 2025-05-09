# All Tables

## Users

- id
- login-name
- login-salt
- login-secret (md5hash)

Should follow US_001

## Groups

- id
- name

## Groupmemberships

- id
- user-id
- group-id
- role
- display-name

## Penalties

- target (groupmembership-id)
- amount
- status
- comment
- creator (groupmembership-id)
- date
- supporters (list of groupmembership-ids)
