<template>
    <div>
        <h2>註冊</h2>
        <input placeholder="Email" />
        <input placeholder="Password" type="password" />
        <input placeholder="Nickname" type="text" />
        <button>Sign Up</button>
        <p></p>

        <h2>登入</h2>
        <input placeholder="Email" type="email" />
        <input placeholder="Password" type="password" />
        <button>Sign In</button>
        <p>Token: </p>

        <h2>驗證</h2>
        <input placeholder="Token" />
        <button>Check Out</button>
        <p></p>

        <h2>登出</h2>
        <input placeholder="Token" />
        <button>Sign Out</button>

        <hr />
        <h2>Todo list</h2>
        <div>
            <input placeholder="New Todo" />
            <button>Add Todo</button>
            <ul>
                <li>
                    <input type="text" placeholder="更新值" />
                    <button>Delete</button>
                    <button>Update</button>
                    <button>Toggle Status</button>
                </li>
            </ul>
        </div>
    </div>
</template>