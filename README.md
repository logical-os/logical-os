# logical

> backend · game dev · low-level

---

## languages.nix

```nix
{
  main = [ "cpp" "c" "py" "ts" "java" ];
  inactive = [ "go" "lua" "html" "css" ];
  wantToLearn = [ "zig" "matlab" "ada" "assembly" ];
  tools = [ "vscode" "cmake" "git" "nixos" ];
}
```

---

## hardware-configuration.nix

```nix
{
  host = "Thinkpad P52";

  cpu = "Xeon E-2176M (6 cores, 12 threads)";
  gpu = "NVIDIA Quadro P2000 / Intel(R) UHD Graphics P630";
  memory = "64.0 GB DDR4";
  storage = "Samsung 512GB NVMe";

  peripherals = {
    monitor = "Sceptre K25, 1920x1080 @ 240.30Hz";
    keyboard = "EPOMAKER x AULA F75 Mechanical";
    mouse = "Logitech G502 Hero";
  };
}
```

---

```
"Faith is to believe what you do not yet see;
the reward for this faith is to see what you believe."

  — Saint Augustine of Hippo
```
