# Logic Check:

- Story / Defect acceptance criteria.
- Feature flag.
- API calls failed / error handling.
- Unused code.
- Duplicate existing code - extract & reuse.
- Magic number -> constants if needed.
- MVP design pattern.

# General:

- Avoid hardcoding.
- Remove 'self.' if not needed.
- Remove extra lines if not needed.
- Remove unused / commented code.
- Force unwrap (red flag) -> guard let / if let.
- Ambiguous / breaking constraints.
- Properties / methods access level.
- Check encapsulating: private / private (set).
- Check polymorphism: final class, static.
- Custom code can be replaced with native approach?
- Merge fetch / resolve all merge conflict.

# Naming check:

- Syntax: typo, camelCase, UpperCamelCase (types, protocols), SwiftLint.
- Naming clear and consistent.
- Code should be self-explain / self-documenting, remove unnecessary comments.
- Appropriate names: class, structures, enums, methods, properties.
- Boolean values should start with `is`, `can`, `should`, `will`, ...
- When in doubt - use longer names (adds more information) over shorter names (can bring confusion).
- Every important event in the app should be logged.
- The logs should contain enough information (class, function, parameters, severity).
- Every public function should have a comment.
- Every file contain a copyright.
- Put TODO comments in format: `// TODO: Developer name - Which release - Description`.

# Performance check:

- Remove `import ...` if not needed.
- Remove unused variables / methods.
- Remove all `print()` statements / unnecessary logging.
- Prefer static constants over computed properties. (Need to revisit this point).
- Use strings interpolation with `\()` instead of concatenation `+`.
- Use `isEmpty` instead of `== nil`.
- Use `!` instead of `== false`.
- Instantiate DateFormatter only once.
- Reuse cells.
- Use image caching.
- Use background threads where needed.
- Memory leak / weak reference.
- Closures should use `weak self`.
- Delegates should be `weak`.
- Check if `unowned` is misused.
- Check for any retain cycles.
