# streamlit-highcharts-python

Streamlit component that allows you to embed Highcharts for Python data visualizations in your Streamlit apps.

## Installation instructions

```sh
pip install streamlit-highcharts-python
```

## Usage instructions

```python
import streamlit as st

from streamlit_highcharts import streamlit_highcharts

value = streamlit_highcharts()

st.write(value)
```