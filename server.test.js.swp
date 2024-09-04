js
const request = require('supertest');
const app = require('../server.js');

describe('Test Express server', () => {
  test('GET / should return status 200', async () => {
    const response = await request(app).get('/');
    expect(response.statusCode).toBe(200);
  });
});
