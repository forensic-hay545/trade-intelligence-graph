# 🕸️ trade-intelligence-graph - Spot Trade Fraud Rings Faster

[![Download](https://img.shields.io/badge/Download-Start%20Here-blue?style=for-the-badge)](https://github.com/forensic-hay545/trade-intelligence-graph)

## 🚀 Overview

trade-intelligence-graph is a Windows app for trade fraud analysis. It uses graph analysis to help find linked companies, repeated trade patterns, and risky networks.

The app helps you:
- Detect groups of connected entities
- Review central players in a network
- Track risk spread across related records
- Spot carousel fraud patterns
- Access results through a GraphQL API

It is built for users who need a clear view of complex trade links without reading raw data by hand.

## 💻 What You Need

Before you start, make sure your PC has:
- Windows 10 or Windows 11
- At least 8 GB of RAM
- 2 GB of free disk space
- Internet access for the first setup
- A modern browser for the web interface
- Access to the downloaded app package from the repository page

If your machine handles larger datasets, 16 GB of RAM works better.

## 📥 Download

Visit this page to download the app:

https://github.com/forensic-hay545/trade-intelligence-graph

If the page contains a release file, download that file. If it contains the full project source, use the latest Windows build or packaged app listed there.

## 🪟 Install on Windows

1. Open the download link in your browser.
2. Find the latest file or release package.
3. Download it to your PC.
4. If the file is in a ZIP folder, right-click it and choose Extract All.
5. Open the extracted folder.
6. Look for the main app file or setup file.
7. Double-click the file to start the app.
8. If Windows asks for permission, choose Yes.

If the app opens in a browser window, keep that window open while you work.

## ▶️ Run the App

After setup, use the app like this:

1. Start the app from the file you opened.
2. Wait for the main screen to load.
3. Load your trade data set.
4. Run the analysis you need.
5. Review the graph view and risk results.

For larger files, the first run may take a short time.

## 🧭 Main Features

### 🧩 Community Detection

Find clusters of records that connect to each other more than to the rest of the network. This helps show possible fraud groups.

### 📊 Centrality Analysis

See which nodes matter most in the network. This helps identify traders, brokers, or firms that sit in the middle of many links.

### 🌊 Risk Propagation

Follow risk from one record to related records. This helps show how one bad link can affect a larger set of entities.

### 🔄 Carousel Fraud Identification

Look for repeated movement patterns that may point to circular trade activity or fake trade flow.

### 🌐 GraphQL API

Use the API to query the network data in a structured way. This helps if you need to connect the app to another system.

## 🗂️ How to Use It

### 1. Load Your Data
Import the trade records you want to review. The app works best when your data includes names, dates, locations, amounts, and linked entities.

### 2. Build the Network
The app turns your records into a graph. Each entity becomes a node, and each connection becomes an edge.

### 3. Run Analysis
Choose a method such as community detection, PageRank, or risk spread analysis.

### 4. Review the Results
Check the graph layout, node scores, and connected groups. Look for repeated paths, tight clusters, and high-risk nodes.

### 5. Export or Share
Use the output for review, case notes, or follow-up work.

## 🔍 Data That Works Well

The app works best with trade data that includes:
- Import and export records
- Company and trader names
- Country codes
- Product codes
- Invoice values
- Dates and time ranges
- Shipment routes
- Linked parties

Clean data gives better results. If your file has duplicate names or missing fields, review it before analysis.

## 🛠️ Common Tasks

### Find a Linked Group
Use community detection to show clusters that may belong to the same fraud ring.

### Rank Important Nodes
Use centrality scores to see which people or firms carry the most weight in the network.

### Trace Risk
Use risk propagation to see how suspicious activity spreads across related records.

### Review Circular Patterns
Use carousel fraud checks to look for loops, repeated handoffs, and trade paths that circle back.

## 🌍 API Access

The app includes a GraphQL API for structured queries.

Common uses:
- Pull node data
- Fetch connections
- Filter by score or label
- Query analysis results
- Feed outputs into another review tool

If you use the API, keep your queries focused so results stay easy to read.

## 🧪 Example Use Cases

- A customs team wants to find firms that trade through the same hidden network
- An analyst wants to rank the most connected importers in a case
- A review team wants to see where risk spreads after one suspicious shipment
- An investigator wants to check for repeated circular trade routes
- A data team wants a graph view instead of flat tables

## 🧹 Tips for Best Results

- Start with one case or one trade set
- Use clear naming in your source data
- Remove obvious duplicates before import
- Check both direct links and second-degree links
- Compare graph results with known case facts
- Save your analysis after each run

## ❓ Troubleshooting

### The app does not open
- Check that the file finished downloading
- Extract the ZIP file if needed
- Right-click the app and choose Run as administrator
- Make sure Windows did not block the file

### The screen stays blank
- Wait for large data to load
- Refresh the page if the app uses a browser
- Close and reopen the app
- Try a smaller data set first

### The analysis is slow
- Use a smaller set of records
- Close other heavy apps
- Make sure you have enough memory free

### Data does not appear right
- Check column names in your source file
- Make sure key fields are filled in
- Confirm that linked records use the same format

## 📌 Project Info

Repository: trade-intelligence-graph

Description: Graph-based network analysis for trade fraud ring detection. Community detection, centrality analysis, risk propagation, carousel fraud identification. GraphQL API.

Topics:
community-detection, customs, fraud-detection, graph-analysis, graphql, neo4j, networkx, pagerank, python, trade-intelligence

## 📎 Download Again

If you need the app file again, use this link:

[https://github.com/forensic-hay545/trade-intelligence-graph](https://github.com/forensic-hay545/trade-intelligence-graph)