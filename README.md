# Action that sets environment variables

```
      - name: step2
        uses: winksaville/gha-set-env-var
        with:
          env-name: ${{ env.name1 }}
          env-value: ${{ runner.os }}-python-${{ env.name1 }}
```
