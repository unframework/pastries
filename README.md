# pastries

Strudel samples.

## Usage

```
// During development
samples('local:')
// or samples('http://192.168.1.159:5432')

// When done — swap to GitHub
samples('github:unframework/pastries')
```

During dev:

```
npx @strudel/sampler
```

Generate and publish:

```
npx @strudel/sampler --json
git add .
git commit -m "Add samples"
git push origin main
```

## File Layout

Example:

```
samples/
  bd/
    001_kick-hard.wav
    002_kick-soft.wav
  snare/
    001_snare.wav
strudel.json
```
