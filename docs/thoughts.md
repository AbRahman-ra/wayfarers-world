# Key Takeaways

- Two types of endpoints
  - Private (auth)
  - Public (no auth)
- Filtering & sorting
- Unit testing
- Docs
- Relations
  - User <- M2M -> Roles
  - Travel <- O2M -> Tours
- Table name: snake_case, attribute name: camelCase
- UUID not ID
- Money \* 100

- timestamps convert to camelCase
- Deletion?
  - Soft delete
  - Hard delete
    - Cascade
    - Null
    - Restrict
