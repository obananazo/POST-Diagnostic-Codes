# POST Diagnostic Codes Reference

A quick reference guide for interpreting **POST** *(Power-On Self Test)* diagnostic codes—the blinking LEDs and beep patterns your laptop sends when hardware fails during startup.

## What?

When you power on your laptop, it runs a series of hardware checks before the operating system loads. If something fails, your computer can't reach the login screen—but it *can* communicate the problem through:

- **LED blink patterns** — Rapid or rhythmic flashing lights (usually on power buttons or caps lock keys)
- **Beep codes** — A series of short and long beeps from the motherboard speaker

These diagnostic signals tell you what component failed, without needing specialized tools.

## Why?

POST codes let you:

- **Identify the problem** — Is it RAM, CPU, motherboard, or power supply?
- **Decide on next steps** — Some fixes you can DIY; others need a professional
- **Avoid unnecessary repairs** — You'll know exactly what to replace or check

## Quick Start

1. **Power on your laptop** and observe the LED/beep pattern
2. **Find your laptop manufacturer** in [MANUFACTURERS.md](./MANUFACTURERS.md)
3. **Match your pattern** to the diagnostic code
4. **Check the troubleshooting section** for next steps

> **⚠️ Note:** ASUS laptops often use AMI or Phoenix BIOS codes rather than ASUS-specific codes. Check your model's manual if the ASUS section doesn't match your pattern.

## Manufacturer Codes

See [MANUFACTURERS.md](./MANUFACTURERS.md) for detailed tables covering:

- ASUS (LED blink patterns)
- Dell (beep codes)
- HP (LED blink patterns)
- Lenovo (beep codes)
- AMI BIOS (traditional beep codes)
- Phoenix BIOS (beep codes)

## Basic Troubleshooting Before Panicking

Try these quick checks first—they solve ~30% of POST code issues:

1. **Reseat your RAM**
   - Power off completely
   - Unplug the laptop
   - Remove RAM sticks and firmly reinsert them
   - Power on and observe

2. **Check power connections**
   - Make sure the charger is fully plugged in
   - Try a different outlet
   - Inspect the charging port for damage

3. **Look for obvious physical damage**
   - Liquid damage, cracked components, loose cables
   - Check if anything smells burnt

4. **Try a hard reset**
   - Unplug power
   - Hold the power button for 30 seconds
   - Plug back in and try again

If these don't help, use the POST code tables to diagnose the issue.

## When to DIY vs. Call a Pro

| Issue | DIY Friendly? | Notes |
|-------|---------------|-------|
| RAM not detected | ✅ Yes | Reseat or replace DIMM sticks |
| Power supply issue | ❌ No | Requires testing equipment |
| CPU failure | ❌ No | Requires desoldering/soldering |
| Motherboard failure | ❌ No | Complex repair, often not worth cost |
| BIOS corruption | ⚠️ Maybe | Varies by manufacturer; check manual |
| Boot device not found | ✅ Yes | May just need to reinstall OS |

## Common Scenarios

**2 blinks on ASUS?**
→ Check [MANUFACTURERS.md](./MANUFACTURERS.md) under ASUS. Likely RAM issue. Try reseating.

**Continuous rapid beeping?**
→ Usually power supply or motherboard. If it's not a beep pattern from the tables, it might be a thermal alarm. Check if the laptop is overheating.

**Pattern is intermittent?**
→ Likely a loose connection. Reseat RAM, check cables, or try a different power outlet.

## Safety First

⚠️ **Before opening your laptop:**

- Unplug the power adapter completely
- Ground yourself (touch a metal part of the case or wear an anti-static wrist strap)
- Let the laptop cool if it was recently powered on
- Don't force any components—if something doesn't slide out easily, you might be doing it wrong

⛔️ **Never attempt:** CPU replacement, motherboard desoldering, or power supply repair without professional training.

<!-- ## Contributing

Found an error in the codes? Used this guide to fix your laptop? Have a real-world example or tip?

[Contributing guidelines coming soon] -->

## Disclaimer

This guide is for educational and troubleshooting purposes. While POST codes are standardized, variations exist between models and BIOS versions. Always consult your laptop's manual for model-specific information. For expensive repairs or uncertain diagnoses, seek professional help.

## Resources

- [ASUS Support](https://www.asus.com/support)
- [Dell Support](https://www.dell.com/support)
- [HP Support](https://support.hp.com)
- [Lenovo Support](https://support.lenovo.com)
- [Phoenix BIOS Documentation](https://phoenixtech.com/support/)

## License

MIT License — feel free to use, modify, and share.

---

**Last updated:** July 2026
