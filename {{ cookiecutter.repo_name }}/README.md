{{cookiecutter.repo_name}}
==============================
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.{{ cookiecutter.zenodo_data_id }}.svg)](https://doi.org/10.5281/zenodo.{{ cookiecutter.zenodo_data_id }})
[![Build Status](https://travis-ci.com/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name.lower().replace(' ', '_') }}.svg?branch=master)](https://travis-ci.com/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name.lower().replace(' ', '_') }})
[![codecov](https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name.lower().replace(' ', '_') }}/branch/master/graph/badge.svg)](https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name.lower().replace(' ', '_') }})
{% if cookiecutter.open_source_license == 'MIT' %}[![License:MIT](https://img.shields.io/badge/License-MIT-lightgray.svg?style=flt-square)](https://opensource.org/licenses/MIT){% elif cookiecutter.open_source_license == 'BSD-3-Clause' %}[![License:BSD-3-Clause](https://img.shields.io/badge/License-BSD%203--Clause-lightgray.svg?style=flt-square)](https://opensource.org/licenses/BSD-3-Clause)
{% endif %}

Code repository to reproduce results from {{cookiecutter.author_list}} {{cookiecutter.year}} published in {{cookiecutter.journal}}

--------

<p><small>Project based on the <a target="_blank" href="https://github.com/jbusecke/cookiecutter-science-paper">cookiecutter science paper template</a>.</small></p>
