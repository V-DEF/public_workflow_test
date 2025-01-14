# Initialize

## Usage

All required inputs are shown here, to see the optional inputs, take a look in the [action.yaml](./action.yaml).

Update, new line.

```
- name: 'checkout and initialize xyx repository'
  uses: vDEV/checkout-and-initialize-xyx-repository/.github/actions/init@latest
  with:
    token: ${{ secrets.TOKEN }}
```