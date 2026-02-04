# Changelog

All notable changes to this chart will be documented in this file.

## [0.21.7] - 2026-02-03

- [redis]: Adjust condition around serviceAccountName (#945) ([ff1ee15](../../commit/ff1ee15))

## [0.21.6] - 2026-02-03

- Update charts/redis/values.yaml redis (#944) ([d891038](../../commit/d891038))
- [all]: Update documentation to include proper cosign public key ([e42365d](../../commit/e42365d))

## [0.21.5] - 2026-02-02

- [redis]: Implement existingFilePath for acl on redis (#936) ([2945710](../../commit/2945710))

## [0.21.4] - 2026-01-30

- [redis]: Seperate client and server tls certs for liveness and readiness probes (#883) ([e643acf](../../commit/e643acf))

## [0.21.3] - 2026-01-28

- [all]: Update every chart to newest common (#920) ([f8d134d](../../commit/f8d134d))

## [0.21.2] - 2026-01-27

- [oliver006/redis_exporter] Update image to v1.80.2 (#908) ([d8034e2](../../commit/d8034e2))

## [0.21.1] - 2026-01-26

- Fix network policy egress, improve cluster init job reliability (#894) ([cf62236](../../commit/cf62236))

## [0.21.0] - 2026-01-19

- [redis]: Configurable log level through values.yaml (#862) ([3ca6523](../../commit/3ca6523))
- chore: update CHANGELOG.md for merged changes ([2f4496d](../../commit/2f4496d))
- chore: update CHANGELOG.md for merged changes ([4c53b54](../../commit/4c53b54))
- chore: update CHANGELOG.md for merged changes ([6361405](../../commit/6361405))

## [0.20.9] - 2026-01-19

- Update charts/redis/values.yaml redis (#857) ([625d9f5](../../commit/625d9f5))
- chore: update CHANGELOG.md for merged changes ([f11acd9](../../commit/f11acd9))
- chore: update CHANGELOG.md for merged changes ([ada889d](../../commit/ada889d))

## [0.20.8] - 2026-01-19

- don't create secret when acl is enabled (#851) ([21cb78c](../../commit/21cb78c))
- chore: update CHANGELOG.md for merged changes ([604ee92](../../commit/604ee92))
- chore: auto-generate values.schema.json (#850) ([3de3115](../../commit/3de3115))
- chore: update CHANGELOG.md for merged changes ([8cfc620](../../commit/8cfc620))

## [0.20.7] - 2026-01-17

- chore: update CHANGELOG.md for merged changes ([70a510d](../../commit/70a510d))
- Allow disabling egress in network policy, headless service should publish not ready addresses when sentinel is enabled (#843) ([3211908](../../commit/3211908))

## [0.20.6] - 2026-01-09

- chore: update CHANGELOG.md for merged changes ([a971b23](../../commit/a971b23))
- chore: update CHANGELOG.md for merged changes ([f13c915](../../commit/f13c915))
- Include Sentinel port in default service when enabled (#811) ([32afbf1](../../commit/32afbf1))
- chore: update CHANGELOG.md for merged changes ([ae6e4cc](../../commit/ae6e4cc))
- chore: update CHANGELOG.md for merged changes ([4a96127](../../commit/4a96127))
- Update charts/redis/values.yaml redis (#820) ([8bac28e](../../commit/8bac28e))
- chore: update CHANGELOG.md for merged changes ([f2fe777](../../commit/f2fe777))
- chore: update CHANGELOG.md for merged changes ([7b27905](../../commit/7b27905))

## [0.20.5] - 2026-01-08

- [alpine/kubectl] Update image to v1.35.0 (#775) ([4f78b86](../../commit/4f78b86))
- chore: update CHANGELOG.md for merged changes ([1e112ae](../../commit/1e112ae))
- chore: update CHANGELOG.md for merged changes ([414809c](../../commit/414809c))
- chore: auto-generate values.schema.json (#815) ([4135c97](../../commit/4135c97))

## [0.20.4] - 2026-01-08

- Cluster add support for custom conig in redis.conf #756 ([90ed6a7](../../commit/90ed6a7))
- chore: update CHANGELOG.md for merged changes ([28e759e](../../commit/28e759e))
- chore: update CHANGELOG.md for merged changes ([b10cae9](../../commit/b10cae9))
- chore: auto-generate values.schema.json (#813) ([9267d0e](../../commit/9267d0e))
- chore: update CHANGELOG.md for merged changes ([ac8f4a5](../../commit/ac8f4a5))

## [0.20.3] - 2026-01-08

- [redis]: Missing CPU Limit in values.yaml #800 ([b09ce6d](../../commit/b09ce6d))

## [0.20.2] - 2026-01-08

- chore: update CHANGELOG.md for merged changes ([f173e0b](../../commit/f173e0b))
- chore: update CHANGELOG.md for merged changes ([1503bf7](../../commit/1503bf7))
- [redis]: fix prestop failover verification logic (#803) ([4c10918](../../commit/4c10918))

## [0.20.1] - 2026-01-05

- chore: update CHANGELOG.md for merged changes ([fa4d988](../../commit/fa4d988))
- chore: update CHANGELOG.md for merged changes ([6e040a6](../../commit/6e040a6))
- chore: auto-generate values.schema.json (#798) ([91e633c](../../commit/91e633c))
- chore: update CHANGELOG.md for merged changes ([5faa674](../../commit/5faa674))
- chore: update CHANGELOG.md for merged changes ([ec82171](../../commit/ec82171))
- change exporter image to alpine based and fix command rendering (#795) ([63662dc](../../commit/63662dc))

## [0.20.0] - 2026-01-05

- chore: update CHANGELOG.md for merged changes ([3fd8a7a](../../commit/3fd8a7a))
- chore: update CHANGELOG.md for merged changes ([ef9ba07](../../commit/ef9ba07))
- [redis]: support zero-downtime upgrades with Sentinel failover (#782) ([1be7c75](../../commit/1be7c75))

## [0.19.0] - 2026-01-01

- chore: update CHANGELOG.md for merged changes ([217930a](../../commit/217930a))
- chore: update CHANGELOG.md for merged changes ([ad7422d](../../commit/ad7422d))
- chore: auto-generate values.schema.json (#791) ([f4b3275](../../commit/f4b3275))
- chore: update CHANGELOG.md for merged changes ([e6ca29f](../../commit/e6ca29f))
- chore: update CHANGELOG.md for merged changes ([332799f](../../commit/332799f))
- add option to configure auth via acl (#780) ([208eaad](../../commit/208eaad))

## [0.18.0] - 2025-12-23

- chore: update CHANGELOG.md for merged changes ([e0ca85e](../../commit/e0ca85e))
- chore: update CHANGELOG.md for merged changes ([17a8b8a](../../commit/17a8b8a))
- [redis]: add sentinel monitoring (#774) ([00e4fef](../../commit/00e4fef))
- chore: update CHANGELOG.md for merged changes ([fd643ed](../../commit/fd643ed))
- chore: update CHANGELOG.md for merged changes ([b82783b](../../commit/b82783b))

## [0.17.7] - 2025-12-23

- chore: update CHANGELOG.md for merged changes ([b9df2cc](../../commit/b9df2cc))
- [redis]: add missing label for sentinel (#773) ([9df4b00](../../commit/9df4b00))

## [0.17.6] - 2025-12-22

- chore: update CHANGELOG.md for merged changes ([b7f89e2](../../commit/b7f89e2))
- chore: update CHANGELOG.md for merged changes ([6bc99e0](../../commit/6bc99e0))
- [redis]: Implement proxy for non sentinel aware proxies (#703) ([0e2ac9f](../../commit/0e2ac9f))

## [0.17.5] - 2025-12-17

- chore: update CHANGELOG.md for merged changes ([5e82a83](../../commit/5e82a83))
- chore: update CHANGELOG.md for merged changes ([8c639a3](../../commit/8c639a3))
- chore(redis): Bump version to 0.17.5 (#762) ([daa894e](../../commit/daa894e))
- chore: update CHANGELOG.md for merged changes ([2f36405](../../commit/2f36405))
- chore: update CHANGELOG.md for merged changes ([4fa5a56](../../commit/4fa5a56))
- fix(redis): Always set masterauth for non-standalone architectures (#750) ([a8b07f4](../../commit/a8b07f4))
- chore: update CHANGELOG.md for merged changes ([23b03ec](../../commit/23b03ec))
- chore: auto-generate values.schema.json (#757) ([424c2bd](../../commit/424c2bd))

## [0.17.4] - 2025-12-16

- chore: update CHANGELOG.md for merged changes ([87e0273](../../commit/87e0273))
- chore: update CHANGELOG.md for merged changes ([dd14022](../../commit/dd14022))
- add readiness and liveness probes to redis sentinel (#755) ([594cf3d](../../commit/594cf3d))

## [0.17.3] - 2025-12-11

- chore: update CHANGELOG.md for merged changes ([79d5eaa](../../commit/79d5eaa))
- chore: update CHANGELOG.md for merged changes ([87cca85](../../commit/87cca85))
- [redis, valkey,rabbitmq,zookeeper]: allow setting revisionHistoryLimit (#725) ([ac9e1ba](../../commit/ac9e1ba))

## [0.17.2] - 2025-12-11

- chore: update CHANGELOG.md for merged changes ([48cbf93](../../commit/48cbf93))
- chore: update CHANGELOG.md for merged changes ([e8c8153](../../commit/e8c8153))
- fix(redis): prevent password logging in sentinel startup (#731) ([2e85940](../../commit/2e85940))

## [0.17.1] - 2025-12-11

- chore: update CHANGELOG.md for merged changes ([73e51b2](../../commit/73e51b2))
- chore: update CHANGELOG.md for merged changes ([b8cefc8](../../commit/b8cefc8))
- fix(redis): Fix headless-service annotations rendering for empty values (#734) ([4e95aa6](../../commit/4e95aa6))

## [0.17.0] - 2025-12-10

- chore: update CHANGELOG.md for merged changes ([e03556b](../../commit/e03556b))
- chore: update CHANGELOG.md for merged changes ([6b059fb](../../commit/6b059fb))
- [redis]: allow changing revisionHistoryLimit (#723) ([38a4238](../../commit/38a4238))
- chore: update CHANGELOG.md for merged changes ([2e78166](../../commit/2e78166))
- chore: update CHANGELOG.md for merged changes ([3b004ad](../../commit/3b004ad))
- Update charts/redis/values.yaml redis (#716) ([887591b](../../commit/887591b))

## [0.16.7] - 2025-12-09

- chore: update CHANGELOG.md for merged changes ([f8868b3](../../commit/f8868b3))
- chore: update CHANGELOG.md for merged changes ([b28e014](../../commit/b28e014))
- Update charts/redis/values.yaml redis (#713) ([689ef89](../../commit/689ef89))

## [0.16.6] - 2025-12-06

- chore: update CHANGELOG.md for merged changes ([efa3d5c](../../commit/efa3d5c))
- chore: update CHANGELOG.md for merged changes ([4828bdb](../../commit/4828bdb))
- return fqdn for sentinel replicas lookup (#700) (#701) ([76a4a10](../../commit/76a4a10))
- chore: update CHANGELOG.md for merged changes ([1b3a65d](../../commit/1b3a65d))
- chore: update CHANGELOG.md for merged changes ([b0df43c](../../commit/b0df43c))

## [0.16.5] - 2025-12-05

- Fix Redis issue with immutableFields cause by the label addition on volumeClaimTemplate (#695) ([f5ce66f](../../commit/f5ce66f))

## [0.16.4] - 2025-12-03

- chore: update CHANGELOG.md for merged changes ([fffc3d2](../../commit/fffc3d2))
- chore: update CHANGELOG.md for merged changes ([17f253f](../../commit/17f253f))
- metrics service annotation does not work (#687) ([6c053af](../../commit/6c053af))

## [0.16.3] - 2025-12-01

- chore: update CHANGELOG.md for merged changes ([f0a81fa](../../commit/f0a81fa))
- add resources to init-cluster job (#680) ([63f8d22](../../commit/63f8d22))

## [0.16.2] - 2025-12-01

- chore: update CHANGELOG.md for merged changes ([1219e3d](../../commit/1219e3d))
- chore: update CHANGELOG.md for merged changes ([d1978ba](../../commit/d1978ba))
- set save in config if persistence is disabled (#677) ([4fdcde0](../../commit/4fdcde0))

## [0.16.1] - 2025-12-01

- chore: update CHANGELOG.md for merged changes ([acb75b9](../../commit/acb75b9))
- chore: update CHANGELOG.md for merged changes ([834af35](../../commit/834af35))
- [universal] add labels to statefulset pvc-templates (#681) ([87624a5](../../commit/87624a5))

## [0.16.0] - 2025-11-25

- chore: update CHANGELOG.md for merged changes ([f16dc26](../../commit/f16dc26))
- chore: update CHANGELOG.md for merged changes ([524f481](../../commit/524f481))
- Update charts/redis/values.yaml redis to v8.4.0 (minor) (#633) ([96c8dd7](../../commit/96c8dd7))

## [0.15.4] - 2025-11-25

- chore: update CHANGELOG.md for merged changes ([b20979c](../../commit/b20979c))
- chore: update CHANGELOG.md for merged changes ([f481c10](../../commit/f481c10))
- [oliver006/redis_exporter] Update image to v1.80.1 (#655) ([fcb59bc](../../commit/fcb59bc))
- chore: auto-generate values.schema.json (#641) ([cced77e](../../commit/cced77e))
- chore: update CHANGELOG.md for merged changes ([734cb3b](../../commit/734cb3b))
- chore: update CHANGELOG.md for merged changes ([fb2a9cc](../../commit/fb2a9cc))

## [0.15.3] - 2025-11-20

- add option to use ip or hostname for sentinal announce-ip (#639) ([639cd31](../../commit/639cd31))

## [0.15.2] - 2025-11-19

- chore: update CHANGELOG.md for merged changes ([f8a3dd1](../../commit/f8a3dd1))
- chore: update CHANGELOG.md for merged changes ([33bf2b6](../../commit/33bf2b6))
- fix condition in statefulset (#637) ([8b74e74](../../commit/8b74e74))
- chore: update CHANGELOG.md for merged changes ([9c9daa4](../../commit/9c9daa4))
- chore: update CHANGELOG.md for merged changes ([ab89d7d](../../commit/ab89d7d))
- chore: auto-generate values.schema.json (#635) ([36f2dd4](../../commit/36f2dd4))

## [0.15.1] - 2025-11-19

- chore: update CHANGELOG.md for merged changes ([ea8e485](../../commit/ea8e485))
- [redis]: tls support ([963e2b8](../../commit/963e2b8))

## [0.15.0] - 2025-11-19

- Add ServiceAccount (#631) ([328f698](../../commit/328f698))
- chore: update CHANGELOG.md for merged changes ([de70b98](../../commit/de70b98))
- chore: update CHANGELOG.md for merged changes ([47edfb5](../../commit/47edfb5))
- Update charts/redis/values.yaml redis (#624) ([a57d0d7](../../commit/a57d0d7))
- chore: update CHANGELOG.md for merged changes ([26504d9](../../commit/26504d9))
- chore: update CHANGELOG.md for merged changes ([014fde8](../../commit/014fde8))

## [0.14.4] - 2025-11-18

- add templating to all annotations (#608) ([2a78f9d](../../commit/2a78f9d))

## [0.14.3] - 2025-11-18

- chore: update CHANGELOG.md for merged changes ([697cb45](../../commit/697cb45))
- chore: update CHANGELOG.md for merged changes ([53d3901](../../commit/53d3901))
- sentinel use hostnames (#615) ([0a0357b](../../commit/0a0357b))
- chore: update CHANGELOG.md for merged changes ([86bdd5d](../../commit/86bdd5d))
- chore: update CHANGELOG.md for merged changes ([544e9bd](../../commit/544e9bd))
- chore: auto-generate values.schema.json (#616) ([d1d105a](../../commit/d1d105a))

## [0.14.2] - 2025-11-17

- chore: update CHANGELOG.md for merged changes ([005861e](../../commit/005861e))
- chore: update CHANGELOG.md for merged changes ([d658aef](../../commit/d658aef))
- [mongodb/redis/posgres] Add subPath option when using existingClaim (#613) ([8aa277e](../../commit/8aa277e))
- chore: update CHANGELOG.md for merged changes ([f3e1ad1](../../commit/f3e1ad1))
- chore: update CHANGELOG.md for merged changes ([96c472e](../../commit/96c472e))
- chore: update CHANGELOG.md for merged changes ([9923048](../../commit/9923048))

## [0.14.1] - 2025-11-13

- [universal] update readme files (#583) ([e63f5f9](../../commit/e63f5f9))
- chore: update CHANGELOG.md for merged changes ([02081a5](../../commit/02081a5))
- chore: update CHANGELOG.md for merged changes ([9618eff](../../commit/9618eff))
- Update charts/redis/values.yaml redis (#554) ([1737c28](../../commit/1737c28))
- chore: update CHANGELOG.md for merged changes ([9cccb2e](../../commit/9cccb2e))
- chore: update CHANGELOG.md for merged changes ([21d6041](../../commit/21d6041))
- chore: auto-generate values.schema.json (#570) ([a23729e](../../commit/a23729e))

## [0.14.0] - 2025-11-07

- [redis]: Headless Service annotations ([10daf47](../../commit/10daf47))
- chore: update CHANGELOG.md for merged changes ([78cf9bf](../../commit/78cf9bf))
- chore: update CHANGELOG.md for merged changes ([099f401](../../commit/099f401))

## [0.13.4] - 2025-11-04

- Update charts/redis/values.yaml redis (#547) ([f0ba3c6](../../commit/f0ba3c6))

## [0.13.3] - 2025-11-04

- [redis]: fix sidecar auth args ([967558f](../../commit/967558f))
- chore: update CHANGELOG.md for merged changes ([a4d1e7f](../../commit/a4d1e7f))
- chore: update CHANGELOG.md for merged changes ([2c4ecc0](../../commit/2c4ecc0))

## [0.13.2] - 2025-11-04

- Update charts/redis/values.yaml redis to v8.2.3 (patch) (#536) ([2410eff](../../commit/2410eff))
- chore: update CHANGELOG.md for merged changes ([3d3b17a](../../commit/3d3b17a))
- chore: update CHANGELOG.md for merged changes ([ff8e82c](../../commit/ff8e82c))

## [0.13.1] - 2025-11-03

- [oliver006/redis_exporter] Update image to v1.80.0 (#532) ([f357771](../../commit/f357771))
- chore: update CHANGELOG.md for merged changes ([c86f513](../../commit/c86f513))
- chore: update CHANGELOG.md for merged changes ([b74d280](../../commit/b74d280))
- chore: auto-generate values.schema.json (#521) ([fe2d15b](../../commit/fe2d15b))

## [0.13.0] - 2025-10-31

- Implement startup probe ([579459a](../../commit/579459a))
- chore: update CHANGELOG.md for merged changes ([0acfe5d](../../commit/0acfe5d))
- chore: update CHANGELOG.md for merged changes ([91ce68f](../../commit/91ce68f))

## [0.12.1] - 2025-10-31

- Fix probes commands (#511) ([0ac529f](../../commit/0ac529f))
- chore: update CHANGELOG.md for merged changes ([3c4c441](../../commit/3c4c441))
- chore: update CHANGELOG.md for merged changes ([fb351f7](../../commit/fb351f7))

## [0.12.0] - 2025-10-30

- Add support for Redis Cluster (#507) ([c1e9fa8](../../commit/c1e9fa8))
- chore: update CHANGELOG.md for merged changes ([640b0f6](../../commit/640b0f6))
- chore: update CHANGELOG.md for merged changes ([bae5763](../../commit/bae5763))

## [0.11.2] - 2025-10-30

- fix: extraEnvVars parameter in statefulset template (#503) ([b681b99](../../commit/b681b99))
- chore: update CHANGELOG.md for merged changes ([434f326](../../commit/434f326))
- chore: update CHANGELOG.md for merged changes ([d3545cc](../../commit/d3545cc))

## [0.11.1] - 2025-10-29

- fix: metrics sidecar variable expansion (#499) ([af02f4a](../../commit/af02f4a))
- chore: update CHANGELOG.md for merged changes ([aec72a0](../../commit/aec72a0))
- chore: update CHANGELOG.md for merged changes ([5a8f954](../../commit/5a8f954))

## [0.11.0] - 2025-10-29

- Add master service for non-sentinel replication mode (#492) ([cafeccd](../../commit/cafeccd))
- chore: update CHANGELOG.md for merged changes ([8b84f2b](../../commit/8b84f2b))
- chore: update CHANGELOG.md for merged changes ([7bc4166](../../commit/7bc4166))
- chore: auto-generate values.schema.json (#487) ([fffe3af](../../commit/fffe3af))
- chore: update CHANGELOG.md for merged changes ([c7fa503](../../commit/c7fa503))
- chore: update CHANGELOG.md for merged changes ([ad9695d](../../commit/ad9695d))

## [0.10.2] - 2025-10-28

- Add support for extraPorts in Services and StatefulSet (#485) ([1805522](../../commit/1805522))
- chore: update CHANGELOG.md for merged changes ([170dd6a](../../commit/170dd6a))
- chore: update CHANGELOG.md for merged changes ([9227d83](../../commit/9227d83))
- [etcd, rabbitmq, redis, zookeeper] add signature verification documentation to readme (#476) ([91c7310](../../commit/91c7310))
- chore: update CHANGELOG.md for merged changes ([8260788](../../commit/8260788))
- chore: update CHANGELOG.md for merged changes ([402f7bd](../../commit/402f7bd))

## [0.10.0] - 2025-10-28

- [universal] unify extraEnvVars in all charts (#477) ([4aee7b4](../../commit/4aee7b4))
- chore: update CHANGELOG.md for merged changes ([05fdd01](../../commit/05fdd01))
- chore: update CHANGELOG.md for merged changes ([807dd92](../../commit/807dd92))

## [0.9.8] - 2025-10-27

- fix service annotations (#470) ([74d2a99](../../commit/74d2a99))
- chore: update CHANGELOG.md for merged changes ([cb10f6b](../../commit/cb10f6b))
- chore: update CHANGELOG.md for merged changes ([ea886c4](../../commit/ea886c4))
- chore: auto-generate values.schema.json (#466) ([650333f](../../commit/650333f))

## [0.9.7] - 2025-10-26

- Redis / Rabbitmq: add lifecyle hooks ([b253776](../../commit/b253776))
- chore: update CHANGELOG.md for merged changes ([f9c3ff0](../../commit/f9c3ff0))
- chore: update CHANGELOG.md for merged changes ([db2d800](../../commit/db2d800))

## [0.9.6] - 2025-10-23

- [universal] Update annotations, labels, podannotations and podlabel (#454) ([cdb38db](../../commit/cdb38db))
- chore: update CHANGELOG.md for merged changes ([d014098](../../commit/d014098))
- chore: update CHANGELOG.md for merged changes ([a839665](../../commit/a839665))

## [0.9.5] - 2025-10-22

- add service support annotations (#446) ([72e7eb7](../../commit/72e7eb7))
- chore: update CHANGELOG.md for merged changes ([baf1dea](../../commit/baf1dea))
- chore: update CHANGELOG.md for merged changes ([42db63e](../../commit/42db63e))

## [0.9.4] - 2025-10-22

- Update charts/redis/values.yaml redis (#434) ([b833a77](../../commit/b833a77))
- chore: update CHANGELOG.md for merged changes ([4587534](../../commit/4587534))
- chore: update CHANGELOG.md for merged changes ([051ad83](../../commit/051ad83))
- chore: update CHANGELOG.md for merged changes ([1a50307](../../commit/1a50307))

## [0.9.3] - 2025-10-22

- [universal]: Support extra secret templating (#444) ([c2b2024](../../commit/c2b2024))
- chore: update CHANGELOG.md for merged changes ([71d5536](../../commit/71d5536))
- chore: update CHANGELOG.md for merged changes ([74b289b](../../commit/74b289b))

## [0.9.2] - 2025-10-21

- Modifiable cluster domain (#427) ([88652de](../../commit/88652de))
- chore: update CHANGELOG.md for merged changes ([c086532](../../commit/c086532))
- chore: update CHANGELOG.md for merged changes ([1742285](../../commit/1742285))
- [universal] add --upload=true to cosign sign (#437) ([e89e0ee](../../commit/e89e0ee))
- chore: update CHANGELOG.md for merged changes ([48cf77d](../../commit/48cf77d))
- chore: update CHANGELOG.md for merged changes ([cd0be3e](../../commit/cd0be3e))

## [0.9.1] - 2025-10-21

- add support for replication mode without sentinel (#428) ([8cbfff2](../../commit/8cbfff2))
- chore: update CHANGELOG.md for merged changes ([5d1f01a](../../commit/5d1f01a))
- chore: update CHANGELOG.md for merged changes ([fc47c5d](../../commit/fc47c5d))
- [unversal] Add signing informations for artifacthub (#415) ([e761c90](../../commit/e761c90))
- chore: update CHANGELOG.md for merged changes ([ef1ad8c](../../commit/ef1ad8c))
- chore: update CHANGELOG.md for merged changes ([aa678df](../../commit/aa678df))
- chore: update CHANGELOG.md for merged changes ([2998496](../../commit/2998496))

## [0.9.0] - 2025-10-17

- Network policies (#412) ([43c7285](../../commit/43c7285))
- chore: update CHANGELOG.md for merged changes ([1a4f87b](../../commit/1a4f87b))
- chore: update CHANGELOG.md for merged changes ([da866ca](../../commit/da866ca))
- [universal] use a string instead of a boolean (#413) ([c24d26d](../../commit/c24d26d))
- [universal] improve chart artifact annotations (#404) ([37f1c5b](../../commit/37f1c5b))
- chore: update CHANGELOG.md for merged changes ([96dc658](../../commit/96dc658))
- chore: update CHANGELOG.md for merged changes ([80f5de8](../../commit/80f5de8))

## [0.8.5] - 2025-10-17

- [oliver006/redis_exporter] Update image to v1.79.0 (#408) ([11c625a](../../commit/11c625a))
- chore: update CHANGELOG.md for merged changes ([3442284](../../commit/3442284))
- chore: update CHANGELOG.md for merged changes ([0295d80](../../commit/0295d80))

## [0.8.4] - 2025-10-17

- Allow Sentinel authentication to be configured independently from Redis authentication (#403) ([ac12616](../../commit/ac12616))
- chore: update CHANGELOG.md for merged changes ([6ebfa2b](../../commit/6ebfa2b))
- chore: update CHANGELOG.md for merged changes ([a207257](../../commit/a207257))

## [0.8.3] - 2025-10-15

- Add initContainer securityContext and improve security defaults (#397) ([2b5c4bd](../../commit/2b5c4bd))
- chore: update CHANGELOG.md for merged changes ([b54c4f1](../../commit/b54c4f1))
- chore: update CHANGELOG.md for merged changes ([5a2ed20](../../commit/5a2ed20))
- [universal] Rework all schema json (#393) ([79d1439](../../commit/79d1439))
- chore: update CHANGELOG.md for merged changes ([7b3173b](../../commit/7b3173b))
- chore: update CHANGELOG.md for merged changes ([ea7518b](../../commit/ea7518b))

## [0.8.2] - 2025-10-14

- Add additional args (#384) ([6dc59eb](../../commit/6dc59eb))
- chore: update CHANGELOG.md for merged changes ([d81bc22](../../commit/d81bc22))
- chore: update CHANGELOG.md for merged changes ([514e3a7](../../commit/514e3a7))

## [0.8.1] - 2025-10-14

- Fix namespace key prefix on redis pdb (#385) ([6451b4c](../../commit/6451b4c))
- chore: update CHANGELOG.md for merged changes ([420f342](../../commit/420f342))
- chore: update CHANGELOG.md for merged changes ([f594b6b](../../commit/f594b6b))

## [0.8.0] - 2025-10-14

- Add pdb and rootOnlyFilesystem options (#383) ([86b889f](../../commit/86b889f))
- chore: update CHANGELOG.md for merged changes ([1ec9aab](../../commit/1ec9aab))
- chore: update CHANGELOG.md for merged changes ([c9ff4ec](../../commit/c9ff4ec))
- chore: update CHANGELOG.md for merged changes ([86f1d25](../../commit/86f1d25))

## [0.7.0] - 2025-10-14

- Update chart.yaml dependencies for indepentent charts (#382) ([87acfb1](../../commit/87acfb1))
- chore: update CHANGELOG.md for merged changes ([84cf67b](../../commit/84cf67b))
- chore: update CHANGELOG.md for all charts via manual trigger ([6974964](../../commit/6974964))
- chore: update CHANGELOG.md for merged changes ([63b7bfa](../../commit/63b7bfa))
- chore: update CHANGELOG.md for merged changes ([da69e0e](../../commit/da69e0e))
- chore: update CHANGELOG.md for merged changes ([5da1b15](../../commit/5da1b15))

## [0.6.4] - 2025-10-13

- [universal] Fix imagepullsecret in vales.schema.json (#374) ([bcc566c](../../commit/bcc566c))
- [universal]: Fix changelog generation (#354) ([2e973c0](../../commit/2e973c0))

## [0.6.3] - 2025-10-10

- feat: use "common.namespace" (#332) ([6dd8563](../../commit/6dd8563))

## [0.6.2] - 2025-10-09

- fix: better IPv6 compatibility (#296) ([1d3543c](../../commit/1d3543c))
- [mongodb] fix: newline between mongo labels and additional labels (#301) ([ea7937f](../../commit/ea7937f))

## [0.6.1] - 2025-10-09

- [redis , rabbitmq]: Add podAnnotations (#294) ([6d78869](../../commit/6d78869))
- add tests for openshift (#226) ([c80c98a](../../commit/c80c98a))
- [mongodb] feat: add metrics exporter (#243) ([c931978](../../commit/c931978))

## [0.6.0] - 2025-10-09

- Include podLabels in redis statefulset (#274) ([024da55](../../commit/024da55))

## [0.5.7] - 2025-10-09

- Update charts/redis/values.yaml redis to v8.2.2 (patch) (#264) ([f699d00](../../commit/f699d00))

## [0.5.6] - 2025-10-08

- [oliver006/redis_exporter] Update oliver006/redis_exporter to v1.78.0 (#235) ([508fd61](../../commit/508fd61))

## [0.5.5] - 2025-10-08

- Update redis to v8.2.2 (#233) ([363468b](../../commit/363468b))

## [0.5.4] - 2025-10-08

- [redis]: fix dual stack networking issues (#227) ([381bd76](../../commit/381bd76))

## [0.5.3] - 2025-10-06

- Add automatically generated fields to volumeClaimTemplates (#218) ([5f4142b](../../commit/5f4142b))

## [0.5.2] - 2025-10-06

- chore(deps): update redis:8.2.1 Docker digest to 5fa2edb (#188) ([6a72e00](../../commit/6a72e00))

## [0.5.1] - 2025-10-06

- chore(deps): update docker.io/redis:8.2.1 Docker digest to 5fa2edb (#187) ([fe21dc2](../../commit/fe21dc2))

## [0.5.0] - 2025-10-01

- make redis run on openshift (#193) ([cc4d3c3](../../commit/cc4d3c3))

## [0.4.6] - 2025-09-25

- return fqdn for sentinel master lookup (#156) ([00b9882](../../commit/00b9882))

## [0.4.5] - 2025-09-24

- Update CHANGELOG.md ([7691aa0](../../commit/7691aa0))
- requirepass for sentinel cli operations when password is set ([60d1b5c](../../commit/60d1b5c))
- Update CHANGELOG.md ([fcf698f](../../commit/fcf698f))
- Update CHANGELOG.md ([1afe498](../../commit/1afe498))
- Update CHANGELOG.md ([0da41aa](../../commit/0da41aa))
- Update CHANGELOG.md ([8425f12](../../commit/8425f12))
- Update CHANGELOG.md ([2753a1e](../../commit/2753a1e))

## [0.4.4] - 2025-09-23

- Update CHANGELOG.md ([f6ea97b](../../commit/f6ea97b))
- Update CHANGELOG.md ([9bd42ad](../../commit/9bd42ad))
- [redis]: Persistent volume claim retentionpolicy ([1f708a5](../../commit/1f708a5))

## [0.4.3] - 2025-09-23

- Update CHANGELOG.md ([497514f](../../commit/497514f))
- add volumeMounts option for sentinel container ([8499307](../../commit/8499307))

## [0.4.2] - 2025-09-23

- Update CHANGELOG.md ([18008d2](../../commit/18008d2))
- bump up chart patch version ([c436c6d](../../commit/c436c6d))
- Add topologySpreadConstraints option to the chart ([9c9eeeb](../../commit/9c9eeeb))

## [0.4.1] - 2025-09-23

- bump up chart patch version ([a5c9dfb](../../commit/a5c9dfb))
- Add metrics section to the README ([14a37bc](../../commit/14a37bc))

## [0.4.0] - 2025-09-22

- Fix reviews ([87c780c](../../commit/87c780c))
- Update CHANGELOG.md ([dfaff03](../../commit/dfaff03))
- Implement redis service monitoring ([3aec93d](../../commit/3aec93d))

## [0.3.3] - 2025-09-18

- Update CHANGELOG.md ([e60664c](../../commit/e60664c))
- chore: bump chart version ([b8bec46](../../commit/b8bec46))
- feat: bind resource to init-container resources from values ([014db83](../../commit/014db83))
- feat: add init container resources configurable values ([852ac34](../../commit/852ac34))

## [0.3.2] - 2025-09-18

- Update CHANGELOG.md ([025e4b2](../../commit/025e4b2))
- Fix lint ([9943a66](../../commit/9943a66))
- Bump chart version ([a892492](../../commit/a892492))
- Fix pod not restarting after configmap change ([8181649](../../commit/8181649))

## [0.3.1] - 2025-09-17

- Update CHANGELOG.md ([a4c0fd0](../../commit/a4c0fd0))
- fix sentinel conditions. set default to standalone ([bf935fa](../../commit/bf935fa))

## [0.3.0] - 2025-09-15

- Decrease defaults ([572cba9](../../commit/572cba9))
- Bitnami style fail over script ([9b9a395](../../commit/9b9a395))
- Unhardcode ips ([b6e0a4e](../../commit/b6e0a4e))
- Implement suggested improvements ([aeac191](../../commit/aeac191))
- Improve defaults ([b964825](../../commit/b964825))
- Configurable recheck values ([cf31961](../../commit/cf31961))
- Full rework ([a8f4e56](../../commit/a8f4e56))
- Update CHANGELOG.md ([103dbd5](../../commit/103dbd5))
- Sync on restart if sentinel available ([628128e](../../commit/628128e))
- Minor improvements ([016dee2](../../commit/016dee2))
- Update CHANGELOG.md ([4657370](../../commit/4657370))
- Fix invalid master detection ([f1545d9](../../commit/f1545d9))
- Fix roles ([9f6cd01](../../commit/9f6cd01))
- Update CHANGELOG.md ([e572ff3](../../commit/e572ff3))
- fix lint ([c9a0e4f](../../commit/c9a0e4f))
- Bump chart version ([a6ac908](../../commit/a6ac908))
- Implement redis sentinal functionality ([70d64d5](../../commit/70d64d5))

## [0.2.1] - 2025-09-09

- Update CHANGELOG.md ([507c187](../../commit/507c187))
- Bump version ([43dceb2](../../commit/43dceb2))
- Update docker.io/redis:8.2.1 Docker digest to acb90ce ([eb469b0](../../commit/eb469b0))

## [0.2.0] - 2025-09-02

- bump all chart versions for new extraObjects feature ([aaa57f9](../../commit/aaa57f9))
- add extraObject array to all charts ([34772b7](../../commit/34772b7))

## [0.1.8] - 2025-08-31

- Update CHANGELOG.md ([d1c5ba2](../../commit/d1c5ba2))
- Add support for statefulset priorityclassname ([b5847dd](../../commit/b5847dd))

## [0.1.7] - 2025-08-28

- Update CHANGELOG.md ([26bf940](../../commit/26bf940))
- Bump chart version ([395c7d5](../../commit/395c7d5))
- Fix typo in readme ([cce0ea8](../../commit/cce0ea8))

## [0.1.6] - 2025-08-27

- Fix values.yaml / Chart.yaml linting issues ([043c7e0](../../commit/043c7e0))
- Add initial Changelogs to all Charts ([68f10ca](../../commit/68f10ca))

## [0.1.5] - 2025-08-26

- Initial release

