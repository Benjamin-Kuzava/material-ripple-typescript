# material-ripple-typescript

## Usage

```
import { Ripple } from '../helpers/ripple.ts';

export const Button: React.FC = () => {
  const ripple = new Ripple();

  return (
      <button
        type="button"
        onMouseUp={(event) => ripple.create(event, 'dark')}
      >
        Ripple
      </button>
  );
};
```
