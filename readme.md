python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
npm run build
npm start
# or
python -m mypackage
curl -s "http://localhost:3000/health"
# or
mycli command --option value
const client = require('<project>');
client.doThing({ key: 'value' });
curl -X POST http://localhost:3000/items -d '{"name":"x"}' -H "Content-Type: application/json"
npm run lint
npm test
# or
pytest tests/
