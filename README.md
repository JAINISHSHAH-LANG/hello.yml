name: Test Email Named Step

on:
  push:
    branches:
      - main

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v3

      - name: 24f1002326@ds.study.iitm.ac.in
        run: echo "Hello, world!"
# hello.yml
