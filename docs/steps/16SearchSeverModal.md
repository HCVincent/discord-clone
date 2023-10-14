server-sidebar.tsx
    server-search.tsx
        search results by CommandDialog

        if (type === "member") {
            return router.push(`/servers/${params?.serverId}/conversations/${id}`);
        }

        if (type === "channel") {
            return router.push(`/servers/${params?.serverId}/channels/${id}`);
         }

    server-section.tsx
        members-modal.tsx: onKick, onRoleChange
        create-channel-modal.tsx

    server-channel.tsx
        const onClick = () => {
            router.push(`/servers/${params?.serverId}/channels/${channel.id}`);
        };
        edit-channel-model.tsx(not started yet)
        delete-channel-model.tsx(not started yet)

    server-member.tsx
        const onClick = () => {
            router.push(`/servers/${params?.serverId}/conversations/${member.id}`)
        }