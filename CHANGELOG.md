# Change Log

## 1.3.0

- Added Alpine.js v3 support with new directives:
  - `x-effect` - Run side effects when dependencies change
  - `x-ignore` - Prevent Alpine from initializing elements
  - `x-teleport` - Move elements to different parts of the DOM
  - `x-id` - Generate scoped unique IDs
  - `x-modelable` - Expose properties for x-model binding
- Added new magic properties:
  - `$store` - Access global Alpine stores
  - `$root` - Reference root component
  - `$data` - Access component data object
  - `$id` - Generate unique IDs for accessibility
- Added new event modifiers:
  - `.throttle` - Throttle event handlers
  - `.self` - Only trigger on self, not children
  - `.camel` - Convert event name to camelCase
  - `.dot` - Handle events with dots in names
  - `.passive` - Add passive event listeners
  - `.capture` - Use capture phase for events
- Updated CDN snippet to Alpine.js v3
- Updated documentation with all new features

## 1.0.0

- Initial release