# Assorted Macros for roll-20

### STR Check
```
  Note: Variables are notated with a leading $ here. These will need to be replaced with the proper values for your
  character.
```

```
/ooc rolling a STR check
/r d20 + [[floor((@{str} / 5))]]
```

### AGL Check

```
/ooc rolling a AGL check
/r d20 + [[floor((@{agl} / 5))]]
```

### COG Check

```
/ooc rolling a COG check
/r d20 + [[floor((@{cog} / 5))]]
```

### CHR Check

```
/ooc rolling a CHR check
/r d20 + [[floor((@{chr} / 5))]]
```

### Skill Check

```
/ooc rolling a [skill name] check
/r d20 + [[floor((@{$relevant_attr} / 5))]] + [[$skill_level_bonus]]
```

### Melee Attack Roll

```
/r d20 + [[floor((@{str} / 5))]] + [[$fighting_skill_level_bonus]]
```

### Ranged Attack Roll

```
/r d20 + [[floor((@{agl} / 5))] + [[$throwing_or_firing_skill_level_bonus]]
```
