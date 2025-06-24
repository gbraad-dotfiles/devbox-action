gbraad's Dotfiles `devbox` action
=================================

Use dotfiles' `devbox`-command to start distrobox environments

### Usage

```yaml
      - name: Setup environment
        uses: gbraad-dotfiles/install-action@main
        
      - name: Run devbox command
        uses: gbraad-dotfiles/devbox-action@main
        with:
          prefix: fedora
          command: shell
          args: cat /etc/os-release
```

Have a look here for an [example workflows](https://github.com/gbraad-dotfiles/actions-test/blob/main/.github/workflows/test-devbox.yml).
