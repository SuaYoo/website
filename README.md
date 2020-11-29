# [suayoo.com](https://suayoo.com)

## dev

```shell
$ cd public
$ python -m SimpleHTTPServer 8000
```

## deploy

- Add `AWS_S3_BUCKET`, `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` to [GitHub secrets](https://docs.github.com/en/free-pro-team@latest/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-a-repository)
- Push to `main` to trigger [deploy workflow](./.github/workflows/deploy.yml)
