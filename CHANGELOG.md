# Changelog

## 0.6.0

- Added a live build and resource-cost preview before committing a route.
- The preview separates normal transport blocks, Junction/Liquid Junction replacements, bridge spans, and bridge endpoints.
- Added total item requirements from every generated build plan.
- Added liquid Conduit routing for Serpulo and Erekir conduit families and compatible modded Conduit subclasses.
- Added automatic Liquid Junction crossings and official conduit bridge replacement support.
- Added intentional connections to built or planned compatible liquid conduits.
- Added route-edit mode: select a highlighted waypoint and tap a new tile to move it without rebuilding the route manually.
- Failed waypoint moves restore the previous point and route safely.
- Updated README installation instructions to use the public Mosestyle repository URL near the top.

## 0.5.0

- Improved mobile GUI styling and portrait notification wrapping.
- Added quick-drag map movement and hold-to-draw behavior in Forbidden mode.
- Added a bounded path-search retry to reduce intermittent first-attempt failures.

## 0.4.2

- Restored Junction-first behavior for single perpendicular conveyor crossings.
- Bridges are reserved for hard obstacles or crowded multi-line spans.

## 0.4.1

- Added tap-to-tap and freehand forbidden-tile drawing and erasing.

## 0.4.0

- Added automatic bridges, ore fallback, forbidden tiles, route preferences, build-queue awareness, intentional connections, and mobile performance protection.

## 0.3.0

- Added automatic Junction crossings and aligned the HUD icon below AutoDrill.

## 0.2.x

- Added icon-based activation, movable mobile controls, and drill-output avoidance.

## 0.1.0

- Initial waypoint-based A* conveyor routing beta.
