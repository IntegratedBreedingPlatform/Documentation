This file aggregates the changelog files from the different BMS modules.

* [Middleware](#middleware) 
* [Workbench](#workbench)
* [Commons](#commons)

<a name="middleware"></a>
# [Middleware](https://github.com/IntegratedBreedingPlatform/Middleware)

## [13.2](https://github.com/IntegratedBreedingPlatform/Middleware/compare/13.0...13.2)
### Added
- r_package, r_call and r_call_parameter tables to store OpenCPU calls configuration [0fe6dcb](https://github.com/IntegratedBreedingPlatform/Middleware/commit/0fe6dcb632c9da917c2cc261b76adbf1ace671c3)

### Changed
### Removed

# [13.0](https://github.com/IntegratedBreedingPlatform/Middleware/compare/12.0...13.0) 

## [12.5](https://github.com/IntegratedBreedingPlatform/Middleware/compare/12.4...12.5)

### Added
- Roles as containers of permissions
- Make repo public, add [LICENSE](https://github.com/IntegratedBreedingPlatform/Middleware/commit/8fc72b5d5437d3bb611178e60021eaae5394b765)
### Changed
### Removed

## [12.4](https://github.com/IntegratedBreedingPlatform/Middleware/compare/12.3...12.4)

### Added
### Changed
- Fix performance caused by sample count in observation tables [e9a270a](https://github.com/IntegratedBreedingPlatform/Middleware/commit/e9a270a04d50b8f18936ae0ac899824de6b4a322)
### Removed
- persons and users tables in crop. Move data to workbench IBP-2784

## [12.2](https://github.com/IntegratedBreedingPlatform/Middleware/compare/12.0...12.2)

### Added
- About BMS icon link to navbar
### Changed
### Removed
- About BMS (about_bms) sidebar menu
- about_bms workbench_tool

<a name="workbench"></a>
# [Workbench](https://github.com/IntegratedBreedingPlatform/Workbench)

# [13.0](https://github.com/IntegratedBreedingPlatform/Workbench/compare/12.0...13.0) 

## [12.5](https://github.com/IntegratedBreedingPlatform/Workbench/compare/12.4...12.5)

### Added
- Angular 2 frontend: Add router and authorization [82cbb9b](https://github.com/IntegratedBreedingPlatform/Workbench/commit/82cbb9bfcf2a5e151b705cd393a6ccbc3d8dca21)
- Angular 5 frontend: Add authorization [7d5856e](https://github.com/IntegratedBreedingPlatform/Workbench/commit/7d5856e6107a565074ce2fef0bb79d2db185f5ae)
- Create, Edit and list roles with permission tree selector
### Changed
- Load authorities per program [158ff0d](https://github.com/IntegratedBreedingPlatform/Workbench/commit/158ff0d1d8199f34f5ca11c75994baa9137a1180)
### Removed


# [12.0](https://github.com/IntegratedBreedingPlatform/Workbench/compare/11.0...12.0) 

## [11.1](https://github.com/IntegratedBreedingPlatform/Workbench/compare/11.0...11.1)

### Added
- New angular module: label-printing
### Changed
- Manage samples module entry point [eeea1f](https://github.com/IntegratedBreedingPlatform/Middleware/commit/eeea1f2d3343ef5156c4851ab31bef8cd6078bf4)
### Removed
- Remove unused jhipster blueprint code [ac2eae415](https://github.com/IntegratedBreedingPlatform/Workbench/commit/ac2eae41523425ea41fa66a2085268b4eed6b3a7) [18d515d3e](https://github.com/IntegratedBreedingPlatform/Workbench/commit/18d515d3eb759d66f8440c460bb114293e8b40f0)

<a name="commons"></a>
# [Commons](https://github.com/IntegratedBreedingPlatform/Commons)

# [12.0](https://github.com/IntegratedBreedingPlatform/Commons/compare/11.0...12.0) 

## Rule Engine migration
### Added
### Changed
- Move Rule engine (Process codes) from Fieldbook 
- Group generators (SeedSourceGenerator and BreedersCrossIDGenerator) and resolvers in a feature package inside ruleengine 
### Removed
- Refactor Seed Source Generator to remove Workbook dependency from advance

