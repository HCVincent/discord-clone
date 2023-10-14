app\(main)\(routes)\servers\[serverId]\page.tsx
db.server.findUnique
where: {
    name: "general",
},
const initialChannel = server?.channels[0];
return redirect(`/servers/${params.serverId}/channels/${initialChannel?.id}`);
