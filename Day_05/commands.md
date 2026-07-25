# Commands Used

## ss -tuln

Displays listening TCP and UDP ports.

```bash
ss -tuln
```

---

## ss -tulpn

Displays listening ports along with process names.

```bash
ss -tulpn
```

---

## ss -tln | grep :22

Checks if SSH is listening on port 22.

```bash
ss -tln | grep :22
```

---

## netstat -tuln

Alternative command to list open ports.

```bash
netstat -tuln
```
