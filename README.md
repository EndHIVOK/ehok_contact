# EHOK Contact

Integrates RedHen Contact with End HIV OK platform.

## Design considerations

The base module `ehok_contact` should work without needing any other End HIV OK Platform components.

### Required modules

| Name            | Purpose                             |
| --------------- | ----------------------------------- |
| `address`         | Provides address field              |
| `gender`          | Provides gender field               |
| `geofield`        | Provides geofield field             |
| `languagefield`   | Provides languagefield field        |
| `link`            | Provides link (URL) field           |
| `media`           | Provides Media entity and field     |
| `name`            | Provides name field                 |
| `options`         | Provides options field              |
| `redhen_contact`  | Provides RedHen Contact entity      |
| `taxonomy`        | Provides Taxonomy entity and field  |
| `telephone`       | Provides telephone field            |
| `text`            | Provides text field.                |

### Fields types

- Address
- Gender
- Geofield
- Language field
- Link
- Media
- Name field
- Options
- Taxonomy
- Telephone
- Text
- Office hours

## Contact types

- Business owner
- Community member
- Healthcare provider
- Patient

### Fields

Label           | Machine-name    | Type      | Widget      | Formatter   | Help
--------------- | --------------- | --------- | ----------- | ----------- | ----
Legal name      | name_legal      | name      | name        | name        |
Preferred name  | name_preferred  | textfield | plain_text  | plain_text  |


#### Business owner
#### Community member
#### Healthcare provider
#### Patient

## Vocabularies

- Medical specialty

- Occupation

## Demographics

### Age

- How old are you? (1)
  - 0-19
  - 20-39
  - 40-60
  - 61+
  - Prefer not to answer


### Disability

- Do you identify as having a disability as defined under the
[Americans with Disabilities Act](https://adata.org/faq/what-definition-disability-under-ada)?
  - Yes, Cognitive
  - Yes, Emotional
  - Yes, Hearing
  - Yes, Mental
  - Yes, Physical
  - Yes, Visual
  - Yes, Self Identify: _________________
  - No
  - Prefer not to answer


- Does your disability affect how you work? (1)
  - Yes
  - No
  - Prefer not to answer


### Education

- What is your education level?
  - Some high school
  - Some college/technical training
  - Completed college
  - Completed master's degree
  - Completed Ph.D
  - Prefer not to answer


### Gender identity

- Do you consider yourself to be transgender? (1)
  - Yes
  - No
  - Questioning
  - Prefer not to answer


- Do you consider yourself to be gender non-conforming, gender diverse, gender variant, or gender expansive? (1)
  - Yes
  - No
  - Questioning
  - Prefer not to answer


- Are you intersex? (1)
  - Yes
  - No
  - I don't know
  - Prefer not to answer


- Where do you identify on the gender spectrum (check all that apply)?
  -  Woman
  -  Demi-girl
  -  Man
  -  Demi-boy
  -  Non-binary
  -  Demi-non-binary
  -  Genderqueer
  -  Genderflux
  -  Genderfluid
  -  Demi-fluid
  -  Demi-gender
  -  Bigender
  -  Trigender
  -  Multigender/polygender
  -  Pangender/omnigender
  -  Maxigender
  -  Aporagender
  -  Intergender
  -  Maverique
  -  Gender confusion/Gender f*ck
  -  Gender indifferent
  -  Graygender
  -  Agender/genderless
  -  Demi-agender
  -  Genderless
  -  Gender neutral
  -  Neutrois
  -  Androgynous
  -  Androgyne
  -  Self Identify: _________________
  -  Prefer not to answer


### Language

- Choose the language(s) you speak and work with and identify your proficiency
  [___________|v]
  [___________|v]
  (list of all languages, including indigenous languages)
  (fluency levels)
  add as many as appropriate.


### Romantic orientation

- What is your romantic orientation (check all that apply)?
  - Straight
  - Questioning
  - Gay
  - Manromantic/androromantic
  - Lesbian
  - Womanromantic/gyneromantic
  - Queer
  - Poly
  - Aromantic
  - Grayromantic
  - Demiromantic
  - Biromantic
  - Bicurious
  - Triromantic
  - Panromatic
  - Omniromantic
  - Fluid/abroromantic
  - Aroflux
  - Autoromantic
  - Androgyneromantic
  - Self Identify: _________________
  - Prefer not to answer


### Location

- Please choose your country of residence.
  - Dropdown of Countries |v|
  - Prefer not to answer


Which word best describes the area where you live and work? (1)
  - Rural
  - Suburban
  - Urban
  - Prefer not to answer


### Race

- Do you identify as a person of color? (1)
  - Yes
  - No
  - Prefer not to answer


- With which racial background(s) do you identify? (check all that apply)
  - Asian
  - Black
  - Latino
  - Native American
  - Pacific Islander
  - White
  - Self Identify: _________________
  - Prefer not to answer


### Religious identification

- Do you practice, worship, or observe a particular religion (or agnostic/atheist theology)? (1)
  - Yes
  - No
  - Prefer not to answer


- Do you identify as a minority because of your religion (or lack thereof)? (1)
  - Yes
  - No
  - N/A
  - Prefer not to answer


### Socioeconomic class

- Thinking about your childhood, which socio-economic class did you identify with? (1)
  - Working class
  - Lower-middle class
  - Upper-middle class
  - Upper class
  - Prefer not to answer


- Thinking about your current situation, which socio-economic class do you identify with? (1)
  - Working class
  - Lower-middle class
  - Upper-middle class
  - Upper class
  - Prefer not to answer


### Sexual orientation

- What is your sexual orientation (check all that apply)?
  - Straight
  - Questioning
  - Gay
  - Masexual/androsexual
  - Lesbian
  - Womasexual/gynesexual
  - Queer
  - Poly
  - Asexual
  - Graysexual
  - Demisexual
  - Bisexual
  - Bicurious
  - Trisexual
  - Pansexual
  - Omnisexual
  - Fluid/abrosexual
  - Aceflux
  - Autosexual
  - Androgynesexual
  - Self Identify: _________________
  - Prefer not to answer
