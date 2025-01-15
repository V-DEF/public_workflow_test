# Initialize

## Usage

All required inputs are shown here, to see the optional inputs, take a look in the [action.yaml](./action.yaml).

Developer 3: Changes after brunch from dev-02
Developer 1: Changes in action initalisation action.

```
- name: 'checkout and initialize xyx repository'
  uses: vDEV/checkout-and-initialize-xyx-repository/.github/actions/init@latest
  with:
    token: ${{ secrets.TOKEN }}
    path: README-Dev-02.md
```

Developer 2: changes after rename folder
Developer 3: Changes after brunch from dev-02