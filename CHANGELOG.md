## [Unreleased]

## [0.8.0] - 2022-01-02

### Added
- Modifying elevation of roads using <kbd>E</kbd>(perspective) or
  <kbd>S</kbd>(sideview) key
- Trajectory operators can be used on elevated roads

### Changed
- Limit start and end endpoint to be not more than 10km apart

## [0.7.2] - 2021-11-07

### Fixed
- End point constraining of arc geometry

## [0.7.1] - 2021-10-25

### Fixed
- Remove duplicate road vertices
- Subdivide lane faces of long roads to avoid rendering issues

## [0.7.0] - 2021-10-24

### Added
- Operator for creating clothoid (Euler Spiral) roads

### Changed
- The road operators for all geometries are now unified and the mesh is sampled
  along the road coordinate system. This also means that all road operators now
  use the cross section configuration UI and support the selected cross
  sections.

## [0.6.0] - 2021-09-06

### Added
- Presets for road cross sections
- Some typical German standardized RAL and RAA road cross sections (RQ9, RQ11,
  RQ31, RQ36, RQ43.5)

### Fixed
- Export crashing when no trajectories exist

## [0.5.0] - 2021-08-30

### Added
- Operator for creating NURBS trajectories

### Fixed
- Path pointing from .xosc file to .xodr file (LogicFile path) not being written
  as relative path

## [0.4.0] - 2021-08-25

### Added
- Operator for creating polyline trajectories

### Fixed
- Icon .png files missing in previous releases now contained in repository and
  release .zip file

## [0.3.0] - 2021-08-17

### Added
- Configurable name, color and initial speed for car objects
- Export of car models with different colors

## [0.2.0] - 2021-08-08

### Added
- Option to export meshes as .fbx files
- Option to export meshes as .gltf files
- Configurable number and type of lanes for straight roads
- Configurable road mark type for straight roads (solid and broken)

## [0.1.1] - 2021-06-21

### Fixed
- Avoid exporter crash and display error message if junction is not fully
  connected

## [0.1.0] - 2021-06-11

### Added
- Operator for creating straight line roads
- Operator for creating arc roads
- Operator for creating 4-way junctions
- Road and junction snapping
- Snapping to grid with <kbd>Ctrl</kbd> modifier key
- Solid lane lines for arc and straight roads
- Operator for creating cars
- Export OpenSCENARIO and OpenDRIVE files using scenariogeneration lib
- Export meshes as .osgb files for esmini using osgconv

[Unreleased]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.8.0...HEAD
[0.8.0]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.7.2...v0.8.0
[0.7.2]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.7.1...v0.7.2
[0.7.1]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.7.0...v0.7.1
[0.7.0]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.6.0...v0.7.0
[0.6.0]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/johschmitz/blender-driving-scenario-creator/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/johschmitz/blender-driving-scenario-creator/releases/tag/v0.1.0
