# Resurrection Cup Showcase Overlay
As the repository name said.

## Install instruction
- Download the latest release
- Extract the contents of the zip file and put them in a folder called `ResCupShowcase`
- Copy the `ResCupShowcase` folder to `<your_gosumemory_path>/static/`
- Run osu!, gosumemory and OBS
- In OBS, add a `Browser Source` with using the URL `http://127.0.0.1:24050/ResCupShowcase`. The source dimension should be `1920x1080`
  
## Edit the Mappool
- Open `ResCupShowcase/mappool.json`
- Edit the mappool

## Update the Overlay
- Redo the `Install instructions`

## Developing
- Clone the repository by `git clone https://github.com/FukutoTojido/Resurrection-Cup-Showcase.git`
- Install all NPM packages by `npm i`
- Start the overlay with `npm run dev`
- To build the overlay, simply run `npm run build`, a `dist` folder will be created with all the assets needed for gosumemory.