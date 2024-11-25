# Short description of this Composite Action
description: Template repository of composite GitHub Action

## About

This action runs setup for SDK and maven setting.

## Usage

### Setup Java and Maven

```yml
      - name: Set up JDK 17 and Maven
        uses: ./.github/reusable-steps
        with:
          github_actor: ${{ github.actor }}
          access_token: ${{ secrets.TEST_ACCESS_TOKEN }}
```

## Support

@stchoupkoua/pipeline-test

## Copyright

Copyright (C) 2024 SkyEngPro
