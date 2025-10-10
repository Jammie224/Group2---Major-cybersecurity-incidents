# WannaCry? Ransomware

### What It Did

**WannaCry** was a ransomware attack launched in May 2017.

- It encrypted files on infected computers, making them inaccessible.

- Victims saw a ransom note demanding Bitcoin payment (≈ $300–$600) to decrypt their files.

- File extensions were changed to .WNCRY, .WNCRYT, or .WNCRY!, and a red ransom screen appeared.

**INSERT IMAGE HERE**

### How It Spread

WannaCry spread automatically and rapidly across networks without user interaction, exploiting a Windows vulnerability.

- It used a Windows exploit called EternalBlue, developed by the U.S. National Security Agency (NSA) and later leaked by a hacker group named Shadow Brokers.

- The exploit targeted a flaw in SMB (Server Message Block) protocol — specifically in Windows XP through Windows 8 and Windows Server 2003–2012.

- Once a computer was infected, it scanned nearby systems on the same network or over the internet and infected them automatically.

### Consequences

**WannaCry** caused global disruption within hours.

Impact highlights:

Over **230,000** computers in 150+ countries were infected.

Major organizations affected included:

UK’s National Health Service (NHS) — hospitals were forced to cancel appointments and divert emergency patients.

FedEx, Renault, Telefonica, Nissan, and Deutsche Bahn were also hit.

Estimated damages: hundreds of millions to billions of dollars in lost productivity and recovery costs.

### How It Was Stopped / Reversed

Kill Switch Activation:

A cybersecurity researcher known online as MalwareTech discovered that WannaCry connected to an unregistered domain name during its operation.

He registered that domain, which unintentionally triggered a built-in “kill switch” in the malware, stopping it from spreading further.

This halted the original WannaCry outbreak almost immediately.

Patching Systems:

Microsoft released emergency security patches (including for unsupported systems like Windows XP) to close the EternalBlue vulnerability (MS17-010).

Organizations that applied these patches became immune to the attack vector.

Decryption Tools (Limited Help):

Some decryption tools were later created (like WannaKey and WannaKiwi) that could recover keys only if the infected computer wasn’t rebooted.

But for most victims, recovery required restoring from backups.

