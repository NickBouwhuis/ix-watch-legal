---
title: Terms
version: "1.0"
effective: 2026-10-13
---

# ix.watch Terms

The rules for using ix.watch: the site, the API and its data, alerts, and sensors.
By using any of them you agree to these terms. How we handle personal data is on the [privacy page](https://ix.watch/privacy).

## Who we are

ix.watch is run by Bouwhuis IT, Piet Heinstraat 12, 7511 JE Enschede, the Netherlands. KvK 64554643, VAT NL002325544B61.
Questions about the service go to [noc@ix.watch](mailto:noc@ix.watch); privacy questions go to [privacy@ix.watch](mailto:privacy@ix.watch).

## What ix.watch is

ix.watch watches IXP peering LANs, from our own ports and from sensors other networks run, and lists the networks sending
traffic that doesn't belong there. The site and the API are free and need no account.

We do this as best we can, with no guarantees. A capture can be down, a frame can be missed, and a MAC can be tied to the wrong network:
member lists, PeeringDB and bgp.tools are sometimes out of date. A listing says what we saw, not that a network did anything wrong on purpose,
and a clean listing doesn't mean a LAN is clean. If we got your network wrong, mail us and we'll fix it.

## Using the API and the data

- You may use, copy and republish what the site and the API publish, including in your own tools and reports, as long as you credit ix.watch.
  What we take from others, such as network names from PeeringDB and bgp.tools and vendor names from the IEEE's MAC address registry,
  stays under its source's terms.
- Keep it to a reasonable load: follow the event stream for live data instead of polling the snapshot several times a second.
  We may limit or block clients that hurt the service for everyone else, without notice.
- Don't use the data to attack, harass or embarrass a network or the people behind it. Use it to get stray traffic fixed.
  The frames and device details are published so their owners can find and fix what sends them, not as a target list.
- Some of the data is personal data (see the [privacy page](https://ix.watch/privacy)). If you keep or republish it, the GDPR applies to you as well:
  don't keep it longer than you need, and remove what we've removed when someone asks.
- The API can change. We try to keep paths and fields working, as with the old `/ix-violators/` paths, but promise no uptime.

## Alerts

Alerts mail a network when its equipment starts or stops leaking onto an IXP we watch, and IXP operators about their whole LAN.
You need a PeeringDB account that may act for the network or IXP, and you're responsible for the addresses you add: only add people who want the mail.

- **Price.** Free for IXP operators, and for networks bgp.tools tags as personal. For other networks, €5 a month or €50 a year per AS number, excluding VAT.
  When bgp.tools stops tagging a network as personal, its alerts stay free for a while, and the alerts page shows until when.
- **Paying.** Payment goes through Stripe. Customers in the EU buy from us as a business and need a valid VAT number:
  reverse charge applies across borders, Dutch VAT within the Netherlands. If the EU's VIES service rejects the number, we stop charging and switch
  the alerts off until it's fixed. Outside the EU, Stripe sells the subscription as the merchant of record, and its terms apply to that sale.
- **Renewal and cancelling.** A subscription renews automatically at the end of each month or year.
  Cancel at any time from the alerts page. Alerts keep running until the end of the period you've paid for, and we don't refund the rest of it.
- **Changes in price.** We tell subscribers by mail at least 30 days before a new price applies to them. You can cancel before it does.
- **What alerts can't do.** They're only as good as the captures behind them. A missed or late alert isn't a breach of these terms.
  If alerts are out for a long time through our fault, mail us and we'll extend your subscription to make up for it.

## Running a sensor

If you run a sensor for us, you need the IXP's permission to capture on its LAN, and you must keep its login to yourself.
The sensor's code is MIT-licensed; the ix.watch name and service aren't. We credit what your sensor sees to the name we agree with you.
We may switch off an account or take an IXP off the site at any time, and you can stop at any time: mail us so we take its IXP off the site.

## Liability

We provide ix.watch as it is. We aren't liable for damage from using it, or from not being able to use it,
including decisions made on what it lists, unless we caused it intentionally or through gross negligence.
For paid alerts, our liability is in any case limited to what you paid us in the 12 months before the damage.
This doesn't limit rights the law doesn't allow us to limit.

## Law, disputes and changes

Dutch law applies to these terms. Disputes go to the court in the Overijssel district (Rechtbank Overijssel),
unless the law gives you the right to go to your own court.

We may change these terms. Each change gets a new version number and the date it takes effect, shown above, and we mail alert subscribers about any change that affects them
at least 30 days before it applies. If a part of these terms turns out to be invalid, the rest still applies.
