# inno-setup-download
Started from pwall2222/inno-setup-download, added new download URL and possibilty to set the InnoSetup License Key.
```yml
      - name: Download and Install InnoSetup
        uses: @TheRich-71/inno-setup-download@v0.0.9
        with:
          version: 6.2.2
```
To apply the Inno Setup Commercial License key, create a GitHub Secret of name INNOSETUPLICENSEKEY
