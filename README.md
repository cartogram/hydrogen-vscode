# Hydrogen VSCode Snippets

## `usq`

Use `useShopQuery()`

```ts
const { data } = useShopQuery({ query: QUERY });
```

## `sq`

New Storefront query

```ts
import gql from "graphql-tag";

const QUERY = gql`
  query Query {
    ...
  }
`;
```

## `imph`

Import from hydrogen

```ts
import {...} from '@shopify/hydrogen';
```

## `hp`

New Hydrogen page

```tsx
function Page {
  return (
    <div>
      ...
    </div>
  )
}

export default Page;
```
