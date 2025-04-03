# Fantasy League Points Matrix

An interactive visualization showing the progression of fantasy league participants across multiple matches. Track points earned, rank changes, and overall standings in a clear, responsive matrix format.

## Features

- Match-by-match point progression
- Real-time rank tracking
- Rank change indicators (↑ up, ↓ down, = maintained)
- Cumulative points display
- Responsive design for all devices
- Dark mode interface

## View Live

Visit [https://hassan-pdesign.github.io/fantasy-league-matrix](https://hassan-pdesign.github.io/fantasy-league-matrix) to see the live version.

## Local Development

To run this project locally:

1. Clone the repository:
```bash
git clone https://github.com/hassan-pdesign/fantasy-league-matrix.git
```

2. Navigate to the project directory:
```bash
cd fantasy-league-matrix
```

3. Open `index.html` in your browser or use a local server:
```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Data Structure

The visualization expects JSON data files in the following structure:
- Located in `02_processed_data/02_overall_stats/`
- Named as `after_match_XX.json` where XX is the match number
- Contains cumulative points and ranking information for each participant

## License

MIT License - Feel free to use and modify as needed. 