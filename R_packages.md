# Single quotes around package names

- In all 'CRAN-facing' places (DESCRIPTION, man/, vignettes/), package names
  should be surrounded with single quotes. In all other places (README.Rmd,
  GitHub description) these should be omitted.

# Referring to functions

- Functions should always be surrounded with back ticks and be suffixed with parentheses.

# Referring to arguments

- Arguments should always be surrounded with back ticks.

# Referring to values

- Logical values should always be surrounded with back ticks. Non-logical
  values should be surrounded with single quotes if outside the context of
  other code, but should be included in backticks otherwise.

# Referring to aesthetic names

- Aesthetic names should always be surrounded with back ticks.

# `@param`

`@param` lines should always end with a period.

# Quotes

Single quotes are preferred outside of verbatim code. Double quotes are
preferred inside verbatim code.
