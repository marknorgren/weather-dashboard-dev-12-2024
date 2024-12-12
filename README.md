# React Site Base

## Project Overview

This is a basic React-based weather application.


## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Copy `.env.sample` to `.env` and configure your OpenWeatherMap API key
4. Start the development server: `npm run dev`

## Technical Implementation Exercise

Choose ONE of the following features to implement. Your implementation should demonstrate software engineering best practices, including proper error handling, testing, and documentation.

### Feature Options:

1. **Weather Data Stubbing System**
   - Implement a stubbing system for weather data that:
     - Provides predictable test data
     - Can be enabled/disabled via environment variables
     - Includes varied responses for different cities
     - Simulates network delays for realism
   - Document the differences between stubs, mocks, and fakes
   - Add example usage patterns
   - Implement fallback behavior for API failures

2. **Caching System**
   - Update to use in-memory cache
   - Implement TTL-based cache invalidation
   - Add cache hit/miss metrics

3. **Advanced Metrics Dashboard**
   - Create a new `/metrics` endpoint displaying:
     - Request latency histograms
     - Cache hit/miss rates
     - Error rates by endpoint
     - Rate limiting statistics

4. **Multi-City Weather Comparison**
   - Add ability to search and compare up to 4 cities
   - Display side-by-side weather comparisons
   - Implement a responsive grid layout
   - Add temperature trend charts using a charting library
   - Include min/max temperature forecasts

5. **Dark Mode**
   - Add a dark mode toggle
   - Implement dark mode styles
   - Utilize CSS variables for easy customization

6. **Location-Based Weather Features**
   - Add geolocation support
   - Implement reverse geocoding to get city from coordinates
   - Add nearby cities suggestions

7. **Add Unit Tests**
   - Setup unit tests
   - Implement integration tests
   - Edge case handling
   - Test coverage report
  
8. **Add a component to show the high and low temp Cities**
   - Create a component that will show the high temp
   - Create a component that will show the low temp
   - Create a component that will show both

## Evaluation Criteria

1. **Code Quality**
  - Clean, readable, and well-organized code
  - Proper error handling
  - TypeScript types and interfaces
  - Code reusability

1. **Testing**
  - Unit tests for new functionality
  - Integration tests where appropriate
  - Edge case handling
  - Test coverage report

1. **Technical Design / Analysis**
  - Architecture decisions
  - Performance considerations
  - Scalability approach
  - Security measures

1. **Documentation**
  - Clear README updates
  - API documentation
  - Setup instructions
  - Design decisions explanation

## Submission Guidelines

1. Create a new branch for your implementation
2. Write clear commit messages
3. Include a brief write-up explaining:
   - Which feature you chose and why
   - Your implementation approach
   - Any trade-offs you made
   - What you would do differently with more time
4. Create a pull request with your changes

## Additional Notes

- Feel free to add any necessary dependencies
- You can refactor existing code if needed
- Focus on quality over quantity
- Consider edge cases and error scenarios

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- OpenWeatherMap API key
