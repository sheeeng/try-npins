# try-npins

```shell
nix-shell --packages npins --run "npins init;"

npins add github ryantm agenix --branch main

# npins add github nixos nixpkgs --branch release-25.05
npins add github nixos nixpkgs --branch master

# npins add github nix-community home-manager --branch release-25.05
npins add github nix-community home-manager --branch master

# npins add github nix-darwin nix-darwin --branch nix-darwin-25.05
npins add github nix-darwin nix-darwin --branch master

npins update --full

npins upgrade
```

```shell
npins add github nixos nixpkgs --branch nixos-unstable --name nixpkgs-nixos-unstable
npins remove nixpkgs-nixos-unstable

npins add github nixos nixpkgs --branch nixpkgs-25.05-darwin --name nixpkgs-nixpkgs-25.05-darwin
npins remove nixpkgs-nixpkgs-25.05-darwin
```
