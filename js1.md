https://www.youtube.com/watch?v=f8Z9JyB2EIE
https://www.youtube.com/watch?v=ZN-HSQgv17s
https://www.youtube.com/watch?v=vLB7r8neQvE
https://www.youtube.com/watch?v=8Xwq35cPwYg&t=45s
https://www.youtube.com/watch?v=LZ_FFvr1DZE
https://www.youtube.com/watch?v=uqebs-Fv5-w
https://www.youtube.com/watch?v=bCpFbERgj7s
https://www.youtube.com/watch?v=PIX719OMz9o
https://www.youtube.com/watch?v=RFWJM8JMXBs
https://www.youtube.com/watch?v=koRKUscJCaQ
https://www.youtube.com/watch?v=AkN6xJcnVYs
https://www.youtube.com/watch?v=rw1xAHJnBV8
https://www.youtube.com/watch?v=7piWmroHgUM
https://www.youtube.com/watch?v=14B85quRQhw
https://www.youtube.com/watch?v=ENnG7GusuO4
https://www.youtube.com/watch?v=xIflplz925Y
TanStack Start
https://www.youtube.com/watch?v=jXyTIQOfTTk
https://youtu.be/jXyTIQOfTTk
https://youtu.be/7i7xmwowwCY
https://youtu.be/jaNGAqh5xkk
https://www.youtube.com/watch?v=S_lID3JVrrs
https://www.youtube.com/watch?v=tLuSFxRdiK4
https://www.youtube.com/watch?v=YNtwaUVtvh0
https://www.youtube.com/watch?v=QDgdUtd6ZRs
https://www.youtube.com/watch?v=uxMADW3CmN4
https://www.youtube.com/watch?v=TKcetuFoYU0
https://www.youtube.com/watch?v=PxWleEgi3Hw
https://www.youtube.com/@SamMeechWard
https://www.youtube.com/watch?v=NCwa_xi0Uuc
https://www.youtube.com/watch?v=RDM-nk5f4SE&t=1760s
https://genezio.com/
services:
  databases:
    - name: db-auth-starter
      region: us-east-1
      type: postgres-neon
postgresql://admin:npg_uglp76KoVbEx@ep-morning-cloud-a4l1mbhg-pooler.us-east-1.aws.neon.tech/db-auth-starter?sslmode=require
npm install pg @types/pg @genezio/types
// Import the postgres driver library at the top of your file
import pg from 'pg'
const { Pool } = pg

// Use the library in your code
const pool = new Pool({
    connectionString: process.env["DB_AUTH_STARTER_DATABASE_URL"],
    ssl: true,
});

await pool.query(
    "CREATE TABLE IF NOT EXISTS users (id SERIAL PRIMARY KEY, name VARCHAR(255))"
);

const name = "John Doe";
await pool.query("INSERT INTO users (name) VALUES ($1)", [name]);
const result = await pool.query("SELECT * FROM users");

console.log(JSON.stringify(result.rows));

notJust․dev
https://www.youtube.com/@notjustdev/playlists
https://www.youtube.com/watch?v=PRdvQt2cbGU
https://www.youtube.com/watch?v=2BtXrJRqF8Y
https://www.youtube.com/watch?v=w_XEPeaetik
https://www.youtube.com/watch?v=vLze97zZKsU
https://www.youtube.com/watch?v=_sSTzz13tVY
https://www.youtube.com/watch?v=VbcuMJVWt_E
https://www.youtube.com/watch?v=EsLocvsxi6I
https://github.com/gbote/CodePlatoon
CodePlatoon
RWD
https://www.youtube.com/watch?v=RDM-nk5f4SE&t=17537s
https://www.youtube.com/watch?v=p55ph0gm3lA
https://www.youtube.com/watch?v=JKwbPZU-FV0
https://www.youtube.com/watch?v=f8Z9JyB2EIE
https://www.youtube.com/watch?v=zAy7bqFUJLg
https://www.youtube.com/watch?v=D7BzTxVVMuw
https://www.youtube.com/watch?v=M5qgFmLRn6U
https://www.youtube.com/watch?v=QiZ62yswdPw
https://www.youtube.com/watch?v=TYB-Lz8YGFk
https://www.youtube.com/watch?v=ix8mMpcrWPQ
https://www.youtube.com/watch?v=0VLAoVGf_74
https://www.youtube.com/watch?v=EXL8mMUXs88
https://www.youtube.com/watch?v=l8knG0BPr-o
https://www.youtube.com/watch?v=ghfSgZ7MQvo
https://www.youtube.com/watch?v=wc9O-9mcObc
https://www.youtube.com/watch?v=zuKbR4Q428o&t=230s
