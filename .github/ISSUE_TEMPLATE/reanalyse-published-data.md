name:        Reanalyse published data
description: Provide parameters for reanalysis of published data
title:       Reanalyse published data
labels:      'reanalysis'
assignees:   ''

- type: input
  id: doi
  attributes:
    label: DOI
    placeholder: e.g., 10.1234/example
  validations:
    required: true

- type: input
  id: analysis_title
  attributes:
    label: Analysis title
    placeholder: Enter the title of the analysis
  validations:
    required: true

- type: dropdown
  id: udg_treatment
  attributes:
    label: UDG treatment
    options:
      - full
      - half
      - none
  validations:
    required: true

- type: dropdown
  id: strandedness
  attributes:
    label: Strandedness
    options:
      - double
      - single
  validations:
    required: true
