# Automated Weather Delay Evidence Gathering Tool

Construction weather delays are common, but proving them is harder than it should be.

## The Problem

Most Site Diary tools let you record a weather delay, but a diary entry alone rarely holds up when a claim is challenged. The standard evidence source is Bureau of Meteorology automated weather station data (timestamped, authoritative, and widely accepted), but only when the weather affecting your site is the same weather affecting the nearest station, which isn't always the case.

Storms don't respect station coverage zones, and a cell can drench one suburb while the next stays dry. If your site is caught in a localised event, the nearest BOM station won't show it, leaving your claim without data support even when work was genuinely impossible.

## What This Tool Does

When a delay is recorded, the tool automatically pulls BOM data for the relevant station and time window and attaches it to the delay record. At the same time, it captures radar and synoptic chart imagery showing cloud cover, rainfall intensity and storm cell movement, compiling it into a timestamped GIF of the event as it tracked across the area, with the site coordinates plotted against it so the relationship between the storm and the site is immediately clear to anyone reviewing the claim.

The result is a contemporaneous, multi-source evidence record that is very difficult to challenge: a diary entry saying work stopped, a BOM record of what the station captured, and a radar GIF showing the storm cell passing directly over the site at that time.

## Why Capture Has to Happen Live

Live radar imagery isn't stored indefinitely, and once a weather event passes the animated map data showing the storm in motion is gone. This tool captures at the time of the event, triggered by the Site Diary entry, so by the time anyone asks for evidence it already exists.

## Status

Open source. Free to use. Built to solve a specific gap that existing construction software does not address.
