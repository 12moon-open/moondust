# moondust

The published dataset of [12moon commons](https://github.com/12moon-open/moonbase). This repository is written by a bot: please do not open pull requests here, report errors in the [`moonbase` issues](https://github.com/12moon-open/moonbase/issues).

> **Status:** early. Streams have not been checked for playback.

## Licence

To the extent possible under law, the contributors have waived all copyright and related rights to this dataset under [CC0 1.0](LICENSE). No attribution is required, though a mention is welcome.

## Layout

```
v1/stations/XX.ndjson   one station per line, sorted by id, one file per country
v1/redirects.ndjson     merged identifiers
```

The format is described in the [data model](https://github.com/12moon-open/moonbase/blob/main/docs/data-model.md). Git history is the record of every published change.

## No warranty

Stream addresses are third-party links, provided as is. Streams belong to their broadcasters. To report a problem, including a rights issue, open a [`moonbase` issue](https://github.com/12moon-open/moonbase/issues).
