# dust-skill-import-duplicate-repro

Test fixture for Dust's GitHub skill import. Two `SKILL.md` files declare the same `name` (`shared-helper`), under `skills/roles/general/` and `skills/roles/im/`. `alpha` and `zeta` have unique names.

See https://github.com/dust-tt/dust/pull/34169.
