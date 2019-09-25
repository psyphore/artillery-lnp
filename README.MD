# iPlatform API Load And Performance

## Resources

[artillery.io docs](https://artillery.io/docs/)

## Signing In Query

Run `artillery run ./signing-in/simple-one.yml report ./signing-in/report/` for signing in simulation

## Dashboard Query

Run `artillery run ./dashboard/simple-one.yml report ./dashboard/report/` for dasboard search simulation

## Rating Query

Run `artillery run -e dev ./rating/simple-one.yml -o ./rating/r1.json -q` for rating simulation for dev environment (`-e dev`)
